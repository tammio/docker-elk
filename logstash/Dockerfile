# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:6.0.0

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

RUN logstash-plugin install logstash-codec-netflow \
    logstash-filter-translate \
    install logstash-filter-cidr \
    install logstash-filter-geoip
