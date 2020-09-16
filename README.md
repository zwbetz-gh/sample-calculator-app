# Sample Calculator App

[![Netlify Status](https://api.netlify.com/api/v1/badges/f962864a-1b92-4234-8664-23a1b7f36dd0/deploy-status)](https://app.netlify.com/sites/sample-calculator-app/deploys)

A sample calculator app

## Demo

<https://sample-calculator-app.netlify.app>

## Setup

1. Fork or download a zip of this repo
1. Install [NodeJS](https://nodejs.org/en/download/) version 12 or higher
1. Install dependencies

        npm install

## Run

1. Start the app at <http://localhost:5000>

        npm run serve

## Run in Docker

1. Build image

        docker build -t sample-calculator-app .

1. Run container

        docker run -i -t --rm -p 5000:5000 --name sample-calculator-app sample-calculator-app