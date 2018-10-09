# Introducing the 310 BTC Bitcoin Challenge

Head over to https://bitcoinchallenge.codes/ for more details.

[!raw image](https://raw.githubusercontent.com/yangboz/bitcoin-puzzles/master/310-btc/challenge.png)

## Solutions:

### 0.1 BTC 

#### ImageMagick

Normalize:http://www.imagemagick.org/script/command-line-options.php#normalize

```
convert -normalize challenge.png challenge_normalized.png
```

Separate:http://www.imagemagick.org/Usage/color_basics/#channels

```
convert -colorspace CMYK -separate challenge_normalized.png challenge_normalized_separated_CMYK_%d.png
```

```
convert -colorspace RGB -separate challenge_normalized.png challenge_normalized_separated_RGB_%d.png 

```


### 0.2 BTC

### 0.31 BTC

### 310 BTC



UPDATES:

- Oct 4 2018: Someone is right on track and moved the funds from the 0.1 BTC address.

A guy called "Lustre" told me he managed to decode it. Good job!

- Oct 9 2018: First successful registration

- Oct 9 2018: The 0.2 BTC wallet was emptied


## references

https://www.reddit.com/r/Bitcoin/comments/9kq7it/introducing_the_310_btc_bitcoin_challenge/

https://www.youtube.com/results?search_query=bitcoin+challenge+310
