FROM elasticsearch:6.5.4

# 停用词: https://www.ranks.nl/stopwords
ENV IK_VERSION 6.5.4
RUN elasticsearch-plugin install -b https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v${IK_VERSION}/elasticsearch-analysis-ik-${IK_VERSION}.zip
