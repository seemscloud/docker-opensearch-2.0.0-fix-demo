FROM opensearchproject/opensearch-dashboards:2.0.0

RUN ./bin/opensearch-dashboards-plugin remove alertingDashboards && \
    ./bin/opensearch-dashboards-plugin install https://github.com/opensearch-project/alerting-dashboards-plugin/files/8835333/alertingDashboards-2.0.0.0.zip