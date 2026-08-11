sometimes re-learning stuff with a different viewpoint is beneficial (and fun!), in this repository, ill be revisiting computer vision through the "Foundations of Computer Vision" book by [Antonio Torralba](https://groups.csail.mit.edu/vision/torralbalab/), [Phillip Isola](https://web.mit.edu/phillipi/), and [William Freeman](https://billf.mit.edu/).

for obvious reasons, this repository is not a fork or copy of the book, but will contain some of my custom exploratory scripts in python, which may or may not directly correlate to the chapters of the book completely (sometimes i might venture too far 😅)

# reading log

## chapter 11 complete

> mon 6 jul

this reading log jumps straight to chapter 11 since i only just started to do reading logs recently with my other repo on cs:app.

imo so far, this book provides an amazing new perspective on computer vision fundamentals, and i got to learn some interesting history too along the way

i realized by reading so far that i missed knowing a huge ton of notation/naming conventions when i was in campus (i.e. i always tried to describe the set of possible outcomes of a training session on the fly, but i realized that there's a term for it: `hypothesis space`) i'm looking forward to meeting lots more stuff like this and be more proficient in communicating with fellow computer vision people

the exercise on making a linear regressor and polynomial regressor essentially from scratch is very neat. it lets me slow down and spend some time "greeting and conversing" with some of the most basic learning algorithms that i have been calling for granted via sklearn.

## chapter 14 complete

> fri, 10 jul

i am humbled by just how much i know about the general sense and direction of how neural nets train, whilst knowing very little about the actual linear algebra and calculus is going on under the hood.

i believe i have a good understanding of how neural nets train on a surface level. my understanding was enough for tinkering around with hyperparameters and or dataset configuration to create very good cv models *(one that im most proud of is the cv model for barunastra's camera perception module, which only trained on ~20 dataset images, augmented to 80, yet work near-flawlessly and outperform those of teams who trained on thousands of images, both in speed and accuracy)*

however, i actually never got to slow down and befriend the calculus of it all (which is working wonders under the hood of things that i can just call via libraries). i am sad to admit that i never got the chance to do extensive calculus on linear/matrix operations during uni (not even sure if that's the right term for it) since it was not part of the curriculum.

for now, i'll continue reading (past chapter 14) in my usual pace, and then when i feel like i've had enough momentum to dive deep into the calculus, ill go back to chapter 9-14 to meticulously implement and or explore the calculus. i really feel like this is one of the biggest gap in my knowledge currently.

## chapter 15 complete

> mon, 10 aug

a very interesting thing i never thought of during my cinematography years is how capturing the impulse response of a recording room can provide an information of the reverberations of the room. perhaps this way there's a way to more intelligently do noise cancellation/removal? i might explore this later.

## [side quest: mit 6.7960]: lecture 2 exercise

> tue, 11 aug

since i have plenty of time to refresh pretty much everything, i might as well! im decided to do a side quest by going through mit's 6.7960 class (deep learning) alongside reading this book, since the class uses this book heavily for reading materials (going through both the book and class might go hand-in-hand in understanding both in a deep level)

i just completed the lecture 2 exercise, and decided to explore a bit further than the exercise's boundary by making an ipynb script of it. i was having an itch to see the subsequent iterations and see the learning process. after the code was done i found myself clicking 'run cell and below' repeatedly on the forward-backward pass section until the loss value is essentially 0 😅
