# Homelab Docker Compose Stack

This repository contains the Docker Compose configuration for my personal homelab.  
It includes reverse proxying, VPN access, monitoring, DNS filtering, S3-compatible storage, container management, and several self-hosted applications.



## Services

- Traefik – reverse proxy with TLS and Cloudflare DNS verification  
- WireGuard Easy – VPN access with a web interface  
- Pi-hole and Cloudflared – DNS filtering with DNS-over-HTTPS upstream  
- Grafana and InfluxDB – monitoring and dashboards  
- Portainer – Docker container management UI  
- MinIO – S3-compatible object storage  
- Homarr – service dashboard  
- Code-Server – VS Code accessible in the browser  
- NGINX Wallpapers – static file hosting for wallpapers

## Security

- All secrets stored in `.env` files and excluded via `.gitignore`  
- Cloudflare DNS token stored as a Docker secret  
- No credentials or sensitive data committed to the repository  


For more details, check out:  
https://daniellincu.dev/homelab/
