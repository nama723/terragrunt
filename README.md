# terragrunt

TERRAGRUNT IS A WRAPPER AROUND TERRAFORM
struucture 
infra/
├── live/
│   ├── dev/
│   │   └── ec2/
│   │       └── terragrunt.hcl
│   ├── staging/
│   │   └── ec2/
│   │       └── terragrunt.hcl
│   └── prod/
│       └── ec2/
│           └── terragrunt.hcl
│
└── modules/
    └── ec2/
        ├── main.tf
        ├── variables.tf
        ├── outputs.tf
        └── versions.tf
