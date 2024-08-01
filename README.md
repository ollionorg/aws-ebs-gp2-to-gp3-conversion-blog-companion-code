![OLLION](https://ollion.com/imgs/logo-black.svg)

# aws-ebs-gp2-to-gp3-conversion
This repository contains a companion script for the blog Maximizing Storage Performance and Savings with Amazon EBS gp3 and Ollion. This script can be used for converting EBS gp2 volumes to gp3 volumes.

A variation of this script could be used in an automated pipeline to update volumes from Amazon EBS gp2 to Amazon EBS gp3. 
However, changes should also be made to existing IAC and deployment pipelines to ensure that all new volumes are provisioned as gp3.
