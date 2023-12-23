## How to run

```bash
terraform plan
terraform apply
```

## IP addresses Table

| Name | IP Address | Port | Description |
|------|------------|------|-------------|
| dnsmasq | 10.10.10.2/24 | 53 | DCHP server |
| cloudflare | 10.10.10.3/24 | | Cloudflare DNS |
| wireguard | 10.10.10.4/24 | 51820 | Wireguard VPN |
| gitea | 10.10.10.5/24 | 3000, 22 | Gitea |
| memos | 10.10.10.6/24 | 5230 | Memos |
| ecc-wiki | 10.10.10.7/24 | 80 | ECC Wiki |
| ecc-blog | 10.10.10.8/24 | 80 | ECC Blog |
