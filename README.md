# Slack Hubot in Docker

Build Hubot in docker with slack addapter.

## Testing

Pre-requisites:

- Slack bot token

To build a docker image

```
docker build -t hubot .
```

To run the docker image

```
docker run -e HUBOT_SLACK_TOKEN=$slack_token hubot
```
