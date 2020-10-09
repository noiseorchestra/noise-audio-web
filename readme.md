# NOISE ORCHESTRA

[Noise Orchestra](https://noiseorchestra.org/) are Manchester sound artists [Vicky Clarke](https://vickyclarke.org/about/) and [David Birchall](https://davidmbirchall.com/), we build Noise Machines that translate light into sound.  Working with light, DIY electronics, turntables and graphical scores, our practice operates at the intersection of art, experimental music and technology, manifesting in performance, DIY instrument making, sound walks, workshops and installations; all inspired by the photo-phonic principles of synthesizing sound from light.

# AUDIO-NOISE-WEB

**This github page documents our experiments with [JackTrip](https://github.com/jacktrip/jacktrip) and the development of accessible devices that create a networked online multi-person space for playing music, rehearsing and broadcasting with good audio quality and stable low latency.**

More info and background [here](https://noiseorchestra.org/2020/06/22/announcing-rd-project-for-playing-music-online-together/)

We are collecting our research and eventually setup instructions on our [Wiki](https://github.com/noiseorchestra/noise-audio-web/wiki)

Our approach to creating audio-noise-web is one implementation of many different existing technologies, we hope it's useful for your use cases and recommend exploring the ongoing activity dedicated to developing these open network music technologies.

## NOISE-SERVER

The noise-server enables and coordinates connections between peers (people with their own devices or an autonomous-noise-unit). There is a  JackTrip Server running in hub mode and a mixer / panning module for routing peer connections as they join the session. See the code for the autopatcher by [madwort (aka Tom Ward)](https://github.com/madwort) [here](https://github.com/noiseorchestra/jacktrip_pypatcher)


## AUTONOMOUS-NOISE-UNIT

These are Raspberry Pi based devices designed as highly accesible entry points to the noise-server. Each device has built in audio ins and outs and the ability to connect to a running session with one click. See the code [here](https://github.com/noiseorchestra/autonomous-noise-unit) by [Sam Andreae](https://www.samandreae.com).


## Installation & Usage tbc..

## Contributing
[Sam Andreae](https://www.samandreae.com)

[madwort (aka Tom Ward)](https://github.com/madwort)
