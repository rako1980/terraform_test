# terraform_test
Plan output
```terraform
Terraform used the selected providers to generate the following execution plan. Resource actions are indicated with the following symbols:
  + create

Terraform will perform the following actions:

  # module.sandbox_vpc.aws_eip.nat_eip[0] will be created
  + resource "aws_eip" "nat_eip" {
      + allocation_id        = (known after apply)
      + association_id       = (known after apply)
      + carrier_ip           = (known after apply)
      + customer_owned_ip    = (known after apply)
      + domain               = (known after apply)
      + id                   = (known after apply)
      + instance             = (known after apply)
      + network_border_group = (known after apply)
      + network_interface    = (known after apply)
      + private_dns          = (known after apply)
      + private_ip           = (known after apply)
      + public_dns           = (known after apply)
      + public_ip            = (known after apply)
      + public_ipv4_pool     = (known after apply)
      + tags                 = {
          + "Name" = "sandbox_nat_eip"
        }
      + tags_all             = {
          + "Name" = "sandbox_nat_eip"
        }
      + vpc                  = true
    }

  # module.sandbox_vpc.aws_eip.nat_eip[1] will be created
  + resource "aws_eip" "nat_eip" {
      + allocation_id        = (known after apply)
      + association_id       = (known after apply)
      + carrier_ip           = (known after apply)
      + customer_owned_ip    = (known after apply)
      + domain               = (known after apply)
      + id                   = (known after apply)
      + instance             = (known after apply)
      + network_border_group = (known after apply)
      + network_interface    = (known after apply)
      + private_dns          = (known after apply)
      + private_ip           = (known after apply)
      + public_dns           = (known after apply)
      + public_ip            = (known after apply)
      + public_ipv4_pool     = (known after apply)
      + tags                 = {
          + "Name" = "sandbox_nat_eip"
        }
      + tags_all             = {
          + "Name" = "sandbox_nat_eip"
        }
      + vpc                  = true
    }

  # module.sandbox_vpc.aws_eip.nat_eip[2] will be created
  + resource "aws_eip" "nat_eip" {
      + allocation_id        = (known after apply)
      + association_id       = (known after apply)
      + carrier_ip           = (known after apply)
      + customer_owned_ip    = (known after apply)
      + domain               = (known after apply)
      + id                   = (known after apply)
      + instance             = (known after apply)
      + network_border_group = (known after apply)
      + network_interface    = (known after apply)
      + private_dns          = (known after apply)
      + private_ip           = (known after apply)
      + public_dns           = (known after apply)
      + public_ip            = (known after apply)
      + public_ipv4_pool     = (known after apply)
      + tags                 = {
          + "Name" = "sandbox_nat_eip"
        }
      + tags_all             = {
          + "Name" = "sandbox_nat_eip"
        }
      + vpc                  = true
    }

  # module.sandbox_vpc.aws_internet_gateway.internet_gw will be created
  + resource "aws_internet_gateway" "internet_gw" {
      + arn      = (known after apply)
      + id       = (known after apply)
      + owner_id = (known after apply)
      + tags     = {
          + "Name" = "sandbox_internet_gw"
        }
      + tags_all = {
          + "Name" = "sandbox_internet_gw"
        }
      + vpc_id   = (known after apply)
    }

  # module.sandbox_vpc.aws_nat_gateway.nat_gw[0] will be created
  + resource "aws_nat_gateway" "nat_gw" {
      + allocation_id        = (known after apply)
      + connectivity_type    = "public"
      + id                   = (known after apply)
      + network_interface_id = (known after apply)
      + private_ip           = (known after apply)
      + public_ip            = (known after apply)
      + subnet_id            = (known after apply)
      + tags                 = {
          + "Name" = "sandbox_nat_gw"
        }
      + tags_all             = {
          + "Name" = "sandbox_nat_gw"
        }
    }

  # module.sandbox_vpc.aws_nat_gateway.nat_gw[1] will be created
  + resource "aws_nat_gateway" "nat_gw" {
      + allocation_id        = (known after apply)
      + connectivity_type    = "public"
      + id                   = (known after apply)
      + network_interface_id = (known after apply)
      + private_ip           = (known after apply)
      + public_ip            = (known after apply)
      + subnet_id            = (known after apply)
      + tags                 = {
          + "Name" = "sandbox_nat_gw"
        }
      + tags_all             = {
          + "Name" = "sandbox_nat_gw"
        }
    }

  # module.sandbox_vpc.aws_nat_gateway.nat_gw[2] will be created
  + resource "aws_nat_gateway" "nat_gw" {
      + allocation_id        = (known after apply)
      + connectivity_type    = "public"
      + id                   = (known after apply)
      + network_interface_id = (known after apply)
      + private_ip           = (known after apply)
      + public_ip            = (known after apply)
      + subnet_id            = (known after apply)
      + tags                 = {
          + "Name" = "sandbox_nat_gw"
        }
      + tags_all             = {
          + "Name" = "sandbox_nat_gw"
        }
    }

  # module.sandbox_vpc.aws_route_table.lambda_function_rt[0] will be created
  + resource "aws_route_table" "lambda_function_rt" {
      + arn              = (known after apply)
      + id               = (known after apply)
      + owner_id         = (known after apply)
      + propagating_vgws = (known after apply)
      + route            = [
          + {
              + carrier_gateway_id         = ""
              + cidr_block                 = "0.0.0.0/0"
              + core_network_arn           = ""
              + destination_prefix_list_id = ""
              + egress_only_gateway_id     = ""
              + gateway_id                 = ""
              + instance_id                = ""
              + ipv6_cidr_block            = ""
              + local_gateway_id           = ""
              + nat_gateway_id             = (known after apply)
              + network_interface_id       = ""
              + transit_gateway_id         = ""
              + vpc_endpoint_id            = ""
              + vpc_peering_connection_id  = ""
            },
        ]
      + tags             = {
          + "Name" = "sandbox_lambda_function_rt_a"
        }
      + tags_all         = {
          + "Name" = "sandbox_lambda_function_rt_a"
        }
      + vpc_id           = (known after apply)
    }

  # module.sandbox_vpc.aws_route_table.lambda_function_rt[1] will be created
  + resource "aws_route_table" "lambda_function_rt" {
      + arn              = (known after apply)
      + id               = (known after apply)
      + owner_id         = (known after apply)
      + propagating_vgws = (known after apply)
      + route            = [
          + {
              + carrier_gateway_id         = ""
              + cidr_block                 = "0.0.0.0/0"
              + core_network_arn           = ""
              + destination_prefix_list_id = ""
              + egress_only_gateway_id     = ""
              + gateway_id                 = ""
              + instance_id                = ""
              + ipv6_cidr_block            = ""
              + local_gateway_id           = ""
              + nat_gateway_id             = (known after apply)
              + network_interface_id       = ""
              + transit_gateway_id         = ""
              + vpc_endpoint_id            = ""
              + vpc_peering_connection_id  = ""
            },
        ]
      + tags             = {
          + "Name" = "sandbox_lambda_function_rt_b"
        }
      + tags_all         = {
          + "Name" = "sandbox_lambda_function_rt_b"
        }
      + vpc_id           = (known after apply)
    }

  # module.sandbox_vpc.aws_route_table.lambda_function_rt[2] will be created
  + resource "aws_route_table" "lambda_function_rt" {
      + arn              = (known after apply)
      + id               = (known after apply)
      + owner_id         = (known after apply)
      + propagating_vgws = (known after apply)
      + route            = [
          + {
              + carrier_gateway_id         = ""
              + cidr_block                 = "0.0.0.0/0"
              + core_network_arn           = ""
              + destination_prefix_list_id = ""
              + egress_only_gateway_id     = ""
              + gateway_id                 = ""
              + instance_id                = ""
              + ipv6_cidr_block            = ""
              + local_gateway_id           = ""
              + nat_gateway_id             = (known after apply)
              + network_interface_id       = ""
              + transit_gateway_id         = ""
              + vpc_endpoint_id            = ""
              + vpc_peering_connection_id  = ""
            },
        ]
      + tags             = {
          + "Name" = "sandbox_lambda_function_rt_c"
        }
      + tags_all         = {
          + "Name" = "sandbox_lambda_function_rt_c"
        }
      + vpc_id           = (known after apply)
    }

  # module.sandbox_vpc.aws_route_table.public_rt will be created
  + resource "aws_route_table" "public_rt" {
      + arn              = (known after apply)
      + id               = (known after apply)
      + owner_id         = (known after apply)
      + propagating_vgws = (known after apply)
      + route            = [
          + {
              + carrier_gateway_id         = ""
              + cidr_block                 = "0.0.0.0/0"
              + core_network_arn           = ""
              + destination_prefix_list_id = ""
              + egress_only_gateway_id     = ""
              + gateway_id                 = (known after apply)
              + instance_id                = ""
              + ipv6_cidr_block            = ""
              + local_gateway_id           = ""
              + nat_gateway_id             = ""
              + network_interface_id       = ""
              + transit_gateway_id         = ""
              + vpc_endpoint_id            = ""
              + vpc_peering_connection_id  = ""
            },
        ]
      + tags             = {
          + "Name" = "sandbox_public_rt"
        }
      + tags_all         = {
          + "Name" = "sandbox_public_rt"
        }
      + vpc_id           = (known after apply)
    }

  # module.sandbox_vpc.aws_route_table_association.private_rta[0] will be created
  + resource "aws_route_table_association" "private_rta" {
      + id             = (known after apply)
      + route_table_id = (known after apply)
      + subnet_id      = (known after apply)
    }

  # module.sandbox_vpc.aws_route_table_association.private_rta[1] will be created
  + resource "aws_route_table_association" "private_rta" {
      + id             = (known after apply)
      + route_table_id = (known after apply)
      + subnet_id      = (known after apply)
    }

  # module.sandbox_vpc.aws_route_table_association.private_rta[2] will be created
  + resource "aws_route_table_association" "private_rta" {
      + id             = (known after apply)
      + route_table_id = (known after apply)
      + subnet_id      = (known after apply)
    }

  # module.sandbox_vpc.aws_route_table_association.public_rta[0] will be created
  + resource "aws_route_table_association" "public_rta" {
      + id             = (known after apply)
      + route_table_id = (known after apply)
      + subnet_id      = (known after apply)
    }

  # module.sandbox_vpc.aws_route_table_association.public_rta[1] will be created
  + resource "aws_route_table_association" "public_rta" {
      + id             = (known after apply)
      + route_table_id = (known after apply)
      + subnet_id      = (known after apply)
    }

  # module.sandbox_vpc.aws_route_table_association.public_rta[2] will be created
  + resource "aws_route_table_association" "public_rta" {
      + id             = (known after apply)
      + route_table_id = (known after apply)
      + subnet_id      = (known after apply)
    }

  # module.sandbox_vpc.aws_subnet.private_subnets[0] will be created
  + resource "aws_subnet" "private_subnets" {
      + arn                                            = (known after apply)
      + assign_ipv6_address_on_creation                = false
      + availability_zone                              = "us-east-1a"
      + availability_zone_id                           = (known after apply)
      + cidr_block                                     = "172.33.100.0/24"
      + enable_dns64                                   = false
      + enable_resource_name_dns_a_record_on_launch    = false
      + enable_resource_name_dns_aaaa_record_on_launch = false
      + id                                             = (known after apply)
      + ipv6_cidr_block_association_id                 = (known after apply)
      + ipv6_native                                    = false
      + map_public_ip_on_launch                        = true
      + owner_id                                       = (known after apply)
      + private_dns_hostname_type_on_launch            = (known after apply)
      + tags                                           = {
          + "Name" = "sandbox_private_subnet_a"
        }
      + tags_all                                       = {
          + "Name" = "sandbox_private_subnet_a"
        }
      + vpc_id                                         = (known after apply)
    }

  # module.sandbox_vpc.aws_subnet.private_subnets[1] will be created
  + resource "aws_subnet" "private_subnets" {
      + arn                                            = (known after apply)
      + assign_ipv6_address_on_creation                = false
      + availability_zone                              = "us-east-1b"
      + availability_zone_id                           = (known after apply)
      + cidr_block                                     = "172.33.110.0/24"
      + enable_dns64                                   = false
      + enable_resource_name_dns_a_record_on_launch    = false
      + enable_resource_name_dns_aaaa_record_on_launch = false
      + id                                             = (known after apply)
      + ipv6_cidr_block_association_id                 = (known after apply)
      + ipv6_native                                    = false
      + map_public_ip_on_launch                        = true
      + owner_id                                       = (known after apply)
      + private_dns_hostname_type_on_launch            = (known after apply)
      + tags                                           = {
          + "Name" = "sandbox_private_subnet_b"
        }
      + tags_all                                       = {
          + "Name" = "sandbox_private_subnet_b"
        }
      + vpc_id                                         = (known after apply)
    }

  # module.sandbox_vpc.aws_subnet.private_subnets[2] will be created
  + resource "aws_subnet" "private_subnets" {
      + arn                                            = (known after apply)
      + assign_ipv6_address_on_creation                = false
      + availability_zone                              = "us-east-1c"
      + availability_zone_id                           = (known after apply)
      + cidr_block                                     = "172.33.120.0/24"
      + enable_dns64                                   = false
      + enable_resource_name_dns_a_record_on_launch    = false
      + enable_resource_name_dns_aaaa_record_on_launch = false
      + id                                             = (known after apply)
      + ipv6_cidr_block_association_id                 = (known after apply)
      + ipv6_native                                    = false
      + map_public_ip_on_launch                        = true
      + owner_id                                       = (known after apply)
      + private_dns_hostname_type_on_launch            = (known after apply)
      + tags                                           = {
          + "Name" = "sandbox_private_subnet_c"
        }
      + tags_all                                       = {
          + "Name" = "sandbox_private_subnet_c"
        }
      + vpc_id                                         = (known after apply)
    }

  # module.sandbox_vpc.aws_subnet.public_subnets[0] will be created
  + resource "aws_subnet" "public_subnets" {
      + arn                                            = (known after apply)
      + assign_ipv6_address_on_creation                = false
      + availability_zone                              = "us-east-1a"
      + availability_zone_id                           = (known after apply)
      + cidr_block                                     = "172.33.10.0/24"
      + enable_dns64                                   = false
      + enable_resource_name_dns_a_record_on_launch    = false
      + enable_resource_name_dns_aaaa_record_on_launch = false
      + id                                             = (known after apply)
      + ipv6_cidr_block_association_id                 = (known after apply)
      + ipv6_native                                    = false
      + map_public_ip_on_launch                        = true
      + owner_id                                       = (known after apply)
      + private_dns_hostname_type_on_launch            = (known after apply)
      + tags                                           = {
          + "Name" = "sandbox_public_subnet_a"
        }
      + tags_all                                       = {
          + "Name" = "sandbox_public_subnet_a"
        }
      + vpc_id                                         = (known after apply)
    }

  # module.sandbox_vpc.aws_subnet.public_subnets[1] will be created
  + resource "aws_subnet" "public_subnets" {
      + arn                                            = (known after apply)
      + assign_ipv6_address_on_creation                = false
      + availability_zone                              = "us-east-1b"
      + availability_zone_id                           = (known after apply)
      + cidr_block                                     = "172.33.20.0/24"
      + enable_dns64                                   = false
      + enable_resource_name_dns_a_record_on_launch    = false
      + enable_resource_name_dns_aaaa_record_on_launch = false
      + id                                             = (known after apply)
      + ipv6_cidr_block_association_id                 = (known after apply)
      + ipv6_native                                    = false
      + map_public_ip_on_launch                        = true
      + owner_id                                       = (known after apply)
      + private_dns_hostname_type_on_launch            = (known after apply)
      + tags                                           = {
          + "Name" = "sandbox_public_subnet_b"
        }
      + tags_all                                       = {
          + "Name" = "sandbox_public_subnet_b"
        }
      + vpc_id                                         = (known after apply)
    }

  # module.sandbox_vpc.aws_subnet.public_subnets[2] will be created
  + resource "aws_subnet" "public_subnets" {
      + arn                                            = (known after apply)
      + assign_ipv6_address_on_creation                = false
      + availability_zone                              = "us-east-1c"
      + availability_zone_id                           = (known after apply)
      + cidr_block                                     = "172.33.30.0/24"
      + enable_dns64                                   = false
      + enable_resource_name_dns_a_record_on_launch    = false
      + enable_resource_name_dns_aaaa_record_on_launch = false
      + id                                             = (known after apply)
      + ipv6_cidr_block_association_id                 = (known after apply)
      + ipv6_native                                    = false
      + map_public_ip_on_launch                        = true
      + owner_id                                       = (known after apply)
      + private_dns_hostname_type_on_launch            = (known after apply)
      + tags                                           = {
          + "Name" = "sandbox_public_subnet_c"
        }
      + tags_all                                       = {
          + "Name" = "sandbox_public_subnet_c"
        }
      + vpc_id                                         = (known after apply)
    }

  # module.sandbox_vpc.aws_vpc.application_vpc will be created
  + resource "aws_vpc" "application_vpc" {
      + arn                                  = (known after apply)
      + cidr_block                           = "172.33.0.0/16"
      + default_network_acl_id               = (known after apply)
      + default_route_table_id               = (known after apply)
      + default_security_group_id            = (known after apply)
      + dhcp_options_id                      = (known after apply)
      + enable_classiclink                   = false
      + enable_classiclink_dns_support       = (known after apply)
      + enable_dns_hostnames                 = true
      + enable_dns_support                   = true
      + id                                   = (known after apply)
      + instance_tenancy                     = "default"
      + ipv6_association_id                  = (known after apply)
      + ipv6_cidr_block                      = (known after apply)
      + ipv6_cidr_block_network_border_group = (known after apply)
      + main_route_table_id                  = (known after apply)
      + owner_id                             = (known after apply)
      + tags                                 = {
          + "Name" = "sandbox_application_vpc"
        }
      + tags_all                             = {
          + "Name" = "sandbox_application_vpc"
        }
    }

Plan: 24 to add, 0 to change, 0 to destroy.

Changes to Outputs:
  + vpc_id = (known after apply)


```
