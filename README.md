# HOW TO RUN CODE

1. Generate AWS_ACCESS_KEY and AWS_SECRET_KEY from IAM with the following permissions
   1. AmazonS3FullAccess [ Required to READ and WRITE to S3 ]

2. Add your access keys in `dl.cfg` file.

2. Change the bucket_name variable in etl.py according to your bucket in S3

3. Run test.ipynb