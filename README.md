# nestedCFStack
This repo consists of Nested Cloud Formation stack scripts, that creates EC2, S3 and chooses Default VPC. 

Created a bucket "ncfbucket11" in S3.
Upload the stackS3.yml in the bucket and copied the objetc URL of the same and gave it as a templateURL in stackRoot for S3 Bucket.
Uploaded stackRoot.yml and StackNested.yml files in the bucket.
While creation of a stack, the Amazon S3 Url is the object URL of the stackRoot.yml
The templateURL is the object URL of the stackNested.yml file.
Make sure all the parameters that have mentioned in the root file, appears in the Parameters section.
This script will take the default VPC available in that region.
