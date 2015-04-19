# Servers-502 repository
502 error pages for services running on back-end servers

# How to deploy it?

To deploy it:
  - Clone the repository with `git clone git@github.com:nasqueron/servers-502.git /var/wwwroot`
  - Edit your web server configuration
      - Declare `/var/wwwroot/sub.domain.tld` as root directory
      - Add a rule to call `502.html` if a 502 error is thrown
