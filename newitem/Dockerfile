FROM almalinux
RUN yum install nginx -y
ADD https://raw.githubusercontent.com/trussworks/terraform-aws-s3-private-bucket/main/main.tf /tmp/
CMD ["nginx", "-g", "daemon off;"]