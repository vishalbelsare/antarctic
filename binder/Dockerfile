# No beakerx support here...
FROM tschm/jupyter as builder

# File Author / Maintainer
MAINTAINER Thomas Schmelzer "thomas.schmelzer@gmail.com"

COPY --chown=jovyan:users  . /tmp/antarctic

RUN pip install --no-cache-dir /tmp/antarctic && \
    pip install --no-cache-dir mongomock && \
    rm  -rf /tmp/antarctic
