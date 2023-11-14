# Terraform / CloudAvenue

## Purpose

This repository is used to manage a <service> on cloudavenue using terraform.

## Usage

- Setup the [cloudavenue provider](https://registry.terraform.io/providers/orange-cloudavenue/cloudavenue/latest/docs#url) in your tf file.
- Include this module in your tf file. Refer to [documentation](https://www.terraform.io/docs/modules/sources.html#generic-git-repository).

```hcl
module "my_service" {
  source  = "cloudavenue-terraform-modules/<module>/cloudavenue"
  version = "0.0.1"

  # insert required variables here
}
```

<!-- BEGIN_TF_DOCS -->
<!-- END_TF_DOCS -->

## Authors

Module is maintained with help from [the community](https://github.com/orange-cloudavenue/module-template/graphs/contributors).
