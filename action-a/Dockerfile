FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello World Obviux!"
LABEL "com.github.actions.description"="This is an awesome description"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="red"

LABEL "repository"="http://github.com/octocat/hello-world"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Octocat <octocat@github.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
