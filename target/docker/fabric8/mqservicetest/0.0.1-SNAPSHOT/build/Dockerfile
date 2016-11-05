FROM jboss-fuse-6/fis-java-openshift:1.0
MAINTAINER docker-maven-plugin@jolokia.org
ENV BROKER_AMQ_TCP_USERNAME=ossl JAVA_MAIN_CLASS=org.apache.camel.cdi.Main JAVA_LIB_DIR=/deployments/lib BROKER_AMQ_TCP_PASSWORD=ossl
COPY maven /deployments/
