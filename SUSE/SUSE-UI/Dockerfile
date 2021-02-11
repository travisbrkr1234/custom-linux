# Set opensuse as base image
FROM opensuse/leap

# Install dependencies
RUN zypper install -y xauth
RUN zypper install -y firefox

#Expose a port number
EXPOSE 8887

# Run firefox
CMD /usr/bin/firefox
