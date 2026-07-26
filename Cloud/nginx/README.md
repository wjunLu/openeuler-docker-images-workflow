# Quick reference
- The official nginx docker image.
- Maintained by: [openEuler](https://atomgit.com/openeuler)

# nginx | openEuler
Current nginx images are built on [openEuler](https://repo.openeuler.org/).

# Supported tags and respective dockerfile links
| Tag | Currently | Architectures |
|-----|-----------|---------------|
| [1.27.2-oe2403lts](https://atomgit.com/openeuler/openeuler-docker-images/blob/master/Cloud/nginx/1.27.2/24.03-lts/Dockerfile) | nginx 1.27.2 on openEuler 24.03-LTS | amd64, arm64 |

# Usage
- Pull the `openeuler/nginx` image:
	```
	docker pull openeuler/nginx:{{Tag}}
	```
- Start:
	```
	docker run -d --name my-nginx -p 80:80 openeuler/nginx:{{Tag}}
	```
- View logs:
	```
	docker logs -f my-nginx
	```
- Interactive shell:
	```
	docker exec -it my-nginx /bin/bash
	```

# Question and answering
If you have any questions, please submit an issue on [openeuler-docker-images](https://atomgit.com/openeuler/openeuler-docker-images).
