This is an alpine-based version of [HT-Editor](http://hte.sourceforge.net/) for Docker.

# Usage

## From Docker Hub
	docker pull razaborg/hte

## Build from Dockerfile
	git clone https://github.com/razaborg/hte-docker.git
	cd hte-docker
	docker build . -t hte

## Run
	docker run -it -v /tmp:/tmp hte ht /tmp/myawesome.bin

