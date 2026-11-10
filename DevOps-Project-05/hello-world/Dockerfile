# Use a specific, stable version instead of latest88
FROM tomcat:9.0-jdk11-corretto

# Copy pre-configured webapps layout securely
RUN cp -R /usr/local/tomcat/webapps.dist/* /usr/local/tomcat/webapps/

# Copy the war file safely using a wildcard fallback
COPY *.war /usr/local/tomcat/webapps/


