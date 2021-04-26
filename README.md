# Shiny Computing Machine Introduction
This package is written to simplfy the process of setting up a local micro-server. The intent is not support a large network, but to augment your local network with some cool features. 

This all started when I bought a pi to install pi hole on. For a while I have had issues with how invasive advirtisments have become. I want to be free to make decisions about my well being without the influence of a marketing major who's job it is to get my money wetheer thier product is the right fit for me or not. 

Later on lockdown came and I was sent home to work from here where I sit. This couch has been my pandemic home and desk. I started to explore the idea of adding other services to my trusted pi hole that had been sanitizing my home network from nasty ads and affiliate links reliabaly for well over a year. 

One day when attemoting to add a service for improving my at home working conditions I addidentally broke a critiacal setting. Rather than learn enough linux to debug the issue I am going to reformat as a new pi and use this as a learning opputunity to explore configutring servers ustilizing docker and docker compose. This will allow a swift rebuild even from total catastrophy. The intent is to get all pi services up and running within 5 minutes of a fresh build, with persisted data, and support for local private environment variables so that others may take inspiration without exposing my private network to attacks.

Wish me luck with that last part. 🤞
## Getting Started

If you wish to run the tutorial, you can use the following command after installing Docker Desktop:

```bash
docker run -d -p 80:80 ryanshores12/shiny-computing-machine
```

Once it has started, you can open your browser to [docker push ryanshores12/shiny-computing-machine:tagname](http://localhost).

## Development

This project has a `docker-compose.yml` file, which will start the mkdocs application on your
local machine and help you see changes instantly.

```bash
docker-compose up
```

## Contributing

If you find typos or other issues with the machine, feel free to create a PR and suggest fixes!
