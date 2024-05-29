ARG BUILD_FROM
FROM $BUILD_FROM

# Setup base
RUN apk add --no-cache py3-paho-mqtt

# Copy data
COPY rootfs /

WORKDIR /tmp
