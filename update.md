# elixir update
=============================UPDATE 17/02/2024===========================

GM Node Operators! There is a new version of the validator software for you to run for Testnet-2. 

Great things are coming over the next couple of weeks, so please make sure your validator is up to date with the latest version of our software. 

The steps for doing this are as follows from the directory with your running Dockerfile:

sudo docker kill ev

sudo docker rm ev

sudo docker pull elixirprotocol/validator:testnet-2

sudo docker build . -t elixir-validator

sudo docker run -it --restart unless-stopped -d --name ev elixir-validator

sudo docker logs -f ev

========================================================================
