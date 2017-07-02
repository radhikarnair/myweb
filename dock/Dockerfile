FROM centos
WORKDIR "/"
USER root
RUN yum install -y httpd ; systemctl enable httpd
#ADD index.html /var/www/html/
EXPOSE 80
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]
