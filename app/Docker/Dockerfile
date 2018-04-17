FROM centos:6
MAINTAINER sagar sagarm2901@gmail.com

RUN yum install wget -y

RUN wget http://repos.fedorapeople.org/repos/dchen/apache-maven/epel-apache-maven.repo -O /etc/yum.repos.d/epel-apache-maven.repo
RUN yum install apache-maven -y
RUN mvn --version
