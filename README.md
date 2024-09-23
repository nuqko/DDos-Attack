I was bored and going through DDOS scripts on github with one of my friends (dont get ddos scripts from here btw, actually buy services you need a botnet), and I saw this absolute pile of crap.
So I removed the uncesscary crap and made it actually work, so you can laugh at it to.

For anyone learning about DDosing, dont use socket to send packets.
- limited to a single thread (slow)
- python is slower than balls
- I/O bound (waits for I/O operations meaning its slower than balls)
- Limited network stack control
- Firewalls will just block the single source anyways.
