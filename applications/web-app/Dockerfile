FROM node:latest
ADD . /app
WORKDIR /app
RUN yarn install
CMD yarn webpack --mode=development --output-path=/tmp/public --watch # this should be configurable based on serve/build
