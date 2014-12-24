## monicore-polymer
The client for monicore in polymer.

## Prerequisites
* Set up [monicore-vagrant](https://github.com/playgrunge/monicore-vagrant)
* Set up and start the golang server [monicore](https://github.com/playgrunge/monicore)

## Installation
```
git clone https://github.com/playgrunge/monicore-ember.git
cd monicore-polymer
sudo npm install
bower install
```

## Running / Development
```
grunt server
```
* http://192.171.0.120:9000/
* http://192.171.0.120:9000/websocketClient.html


## Other
```
# Build your project, creating an optimized build.html
grunt build

# Run any unit tests you might have written
grunt test
```
