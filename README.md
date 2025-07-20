# Terraform

------------------------Terraform variables command ------------------------

terraform destroy -var-file="uat.tfvars"
terraform destroy -var-file="prod.tfvars"
terraform destroy -var-file="uat.tfvars"
terraform apply  -var="instance_type=t2.micro" ----> pass variable through cli