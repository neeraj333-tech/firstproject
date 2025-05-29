# firstproject
provider "aws" {region = "us-west-2"}
resource "aws_instance" "example" { ami = "ami-0c555b159cbfafe1f0" instance_type = "t2.micro" }
