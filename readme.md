# commit

# merge

# stash

# pull

# Learn Maarkown
- ordered list
- autolink
- images
- unordered list
- blockquote
- horizontal rule
- footnote
- strike through
- autolist
- code
- tables

# Unordered list  

We can create undordered list by using hyphen 
- example 1
- example 2 
- example 3 

# Ordered list 
1. foo
2. bar
3) baz


#  Autolink 
https://github.github.com/gfm/#list-items

# Text Formatting 

*italics*

**Bold**

~~strikethrough~~

# code

view all the IP address using the command , note this is using double 
 backtick``ipconfig/all``


 # Multi Line code 

Code goes here after 3 backticks
 ```

terraform {
  required_providers {
    aws = {
      source  = "hashicorp/aws"
      version = "~> 4.16"
    }
  }

  required_version = ">= 1.2.0"
}

provider "aws" {
  region  = "us-west-2"
}

resource "aws_instance" "app_server" {
  ami           = "ami-830c94e3"
  instance_type = "t2.micro"

  tags = {
    Name = "ExampleAppServerInstance"
  }
}


 ````


 ## Tables 
 |hello|hi|
 |---|---|
 |1|2|


 # blockquote
 > first 
   > second
   