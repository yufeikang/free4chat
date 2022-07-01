FROM scratch

ADD config /config
COPY kraken /kraken

EXPOSE 7000

CMD ["/kraken", "-c", "/config/engine.toml", "-s", "engine"]