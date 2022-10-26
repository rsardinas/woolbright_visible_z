FROM tomcat
RUN mkdir /usr/local/tomcat/webapps/visiblez
COPY Runner.jar /usr/local/tomcat/webapps/visiblez
COPY visiblez.jnlp /usr/local/tomcat/webapps/visiblez
COPY index.html /usr/local/tomcat/webapps/visiblez
CMD ["catalina.sh","run"]
