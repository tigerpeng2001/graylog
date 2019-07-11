FROM graylog/graylog:3.0.2
RUN curl  -o /tmp/graylog-enterprise-plugins-3.0.2.tgz -L https://downloads.graylog.org/releases/graylog-enterprise/graylog-enterprise-plugins-3.0.2.tgz; \
    tar -xf /tmp/graylog-enterprise-plugins-3.0.2.tgz -C /tmp; \
    mv /tmp/graylog-enterprise-plugins-3.0.2/plugin/graylog-plugin-enterprise-3.0.2.jar /usr/share/graylog/plugin/; \
    mv /tmp/graylog-enterprise-plugins-3.0.2/bin/* /usr/share/graylog/bin/; \
    rm -rf /tmp/graylog*
