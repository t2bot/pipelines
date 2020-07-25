# pipelines
Pipeline configurations for buildkite

## Agent configuration

1. Follow https://buildkite.com/docs/agent/v3/ubuntu
2. Follow https://docs.docker.com/engine/install/ubuntu/
3. `sudo usermod -aG docker buildkite-agent`
4. `sudo chown -R buildkite-agent:buildkite-agent /var/lib/buildkite-agent/builds`
