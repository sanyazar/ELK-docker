FROM logstash

# add custom config
COPY logstash.conf /config-dir/logstash.conf

# add templates
#COPY ./templates/ /config-dir/templates/
#COPY ./conf.d/ /config-dir/conf.d/
COPY ./logstash/ /etc/logstash/
#COPY ./patterns/ /config-dir/patterns/
#COPY ./patterns/ /etc/logstash/patterns/
