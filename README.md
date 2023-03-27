
provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "<yhnkaya/docker-instance/aws"
    key_name = "insertyourpemkeyhere"
}
