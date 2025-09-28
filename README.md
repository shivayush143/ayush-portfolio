# demo-actions-project

# AWS S3 bucket policy for public access
{
"Version":"2012-10-17",		 	 	 
"Statement": [{
  "Sid": "PublicReadGetObject",
  "Principal": "*",
  "Effect": "Allow",
  "Action": "s3:GetObject",
  "Resource": "arn:aws:s3:::ayush-portfolio1/*",
}
]
}
