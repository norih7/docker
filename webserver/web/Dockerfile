FROM centos
RUN yum -y update && \
    yum -y install httpd php && \
    yum -y install http://dev.mysql.com/get/mysql-community-release-el7-5.noarch.rpm \
    yum -y install mysql-community-server mysql mysql-devel mysql-server mysql-utilities
EXPOSE 80
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
