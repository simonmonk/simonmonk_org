---
layout: "page"
permalink: /prog_pico
---

[Code](https://github.com/simonmonk/prog_pico_ed1) | [Buy on Amazon](https://www.amazon.com/Programming-Pico-Coding-Electronics-Raspberry/dp/B09HG2JYS9) | [Buy on Barnes & Noble](https://www.barnesandnoble.com/w/programming-the-pico-simon-monk/1140636971) | [Buy from Hobby Electronics Retailers](https://www.monkmakes.com/book_prob_pico.html)

his book will teach you Python programming and some basic electronics without assuming any prior knowledge of either subject. The book initially focusses on Python programming, building up a Morse Code example using the Raspberry Pi Pico’s built-in LED. Once you have mastered the basics of coding the Pico, the book will introduce electronics, showing you how to use sensors, switches, LEDs, servomotors and displays attached to your Pico.

![cover](/assets/images/cover_pico.png)

All the parts used in the book are available in a [companion kit](https://www.monkmakes.com/pico_kit1.html) by MonkMakes Ltd. available from suppliers world-wide.


## See Also

[Adafruit blog post](https://blog.adafruit.com/2021/10/13/an-interview-with-simon-monk-author-of-programming-the-pico-python-micropython-raspberrypipico-simonmonk2/)


## Errata

Pg. 3 – the Pico can only supply 300mA, not 800mA (Pico Datasheet pg8).

Pg. 21 – C to F conversion text has 5/9 as the factor, the code has 9/5 (code is correct)

Pico W.

If you have a Pico W rather than the original Pico, the the pin attached to the built-in LED has changed. Please use the constant LED to refer to the built-in LED. For example:

led = Pin(LED, Pin.OUT)
The book’s example code download has also been commented to explain this.