FROM kong:1.4.2-alpine
LABEL description="Kong Alpine with kong-oidc plugin"
RUN apk update && apk add git unzip luarocks
RUN luarocks install kong-oidc