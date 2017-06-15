# MusicKit JWT Token Encoder

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

This is a simple script to sign and encode the JWT developer token used by MusicKit.

## Prerequisites

Before you can use the token encoder, you need to install the [JWT](https://github.com/jwt/ruby-jwt) gem:

```
sudo gem install jwt
```

## Usage

Simply execute the `music-token-encoder` command along with the following parameters:

* Private Key (.p8)
* Key ID
* Team ID
* Token expiration in days (currently: must not be greater than 180)

```
./musickit-token-encoder <KEY>.p8 <KEYID> <TEAMID> 180 
```
