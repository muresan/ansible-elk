FROM docker.elastic.co/kibana/kibana:6.4.2

RUN NODE_OPTIONS="--max-old-space-size=4096" ./bin/kibana-plugin install \
	https://download.elastic.co/kibana/canvas/kibana-canvas-0.1.2200.zip

