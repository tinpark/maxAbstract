# mpAmbiDecoder
This little abstraction is designed to help you switch seamlessly between listening-situations. Sometimes you'll be working on headphones, other times performing for a stereo PA system, occasionally in the 5.1 studio and sometimes somewhere special like a large gallery space with 16 speakers.

mpAmbiDecoder wraps up the [ICST `ambidecode`](https://cycling74.com/tools/icst-ambisonics-tools) Max external into something useful for all of the above situations. As explained in the help patch, it would be very easy to hack this to accommodate higher order of ambisonics in and many more speaker positions than 16. As it is, this is optimised for FuMa bformat input.

The help patch screen shot below is hopefully self explanatory but you should use this as a bpatcher to get the best results from it.

![Screen shot of the help file showing how to wire up `mpAmbiDecode` as part of your patch](images/_mpAmbiDecoder.png).

The bpatcher expects a path input to its left inlet in order to ensure that speaker position presets can be read and written to disk. Again, see the screenshot and `.maxhelp` file for the quickest way to do this. 
