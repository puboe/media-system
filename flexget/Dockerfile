FROM python:3.7

WORKDIR /app

RUN pip install --no-cache-dir transmissionrpc
RUN pip install --no-cache-dir flexget

CMD ["flexget", "daemon", "start"]