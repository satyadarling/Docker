# Use an official Tomcat image from the Docker Hub
FROM tomcat:10.0.20-jdk11-openjdk

# Maintain the container
LABEL maintainer="bhaskarndas@gmail.com"

# Copy the WAR file to the webapps directory of Tomcat
COPY sample.war /usr/local/tomcat/webapps/

# Expose the port on which Tomcat runs
EXPOSE 8080

# Set the default command to run Tomcat
CMD ["catalina.sh", "run"]

