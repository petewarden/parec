# parec
Standalone version of the Pulse Audio simple parec example.

Based on [freedesktop.org/software/pulseaudio/doxygen/parec-simple_8c-example.html](https://freedesktop.org/software/pulseaudio/doxygen/parec-simple_8c-example.html)

## Building and Running

```
sudo apt-get install -y libpulse-dev
gcc parec.c -o parec -lpulse -lpulse-simple
./parec > audio.raw
```