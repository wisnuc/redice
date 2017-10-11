# redice
Demux the multipart/form-data

This library is a derivative work of [dicer](https://github.com/mscdex/dicer) and [streamsearch](https://github.com/mscdex/streamsearch) by Brian White ([@mscdex](https://github.com/mscdex)).

`redice` is not a general purpose library for parsing multipart/form-data. It is designed to de-multiplex multipart/form-data for custom protocols. 

There is nothing wrong in the original work. But in redice, we make the following changes:
1. Explict state machine models are applied to all components.
2. Several design rules for the composing asynchronous objects are enforced. These rules are strictly followed in our company when coding mission-critical parts in system software.
3. ES6 class and JavaScript Standard coding style.




