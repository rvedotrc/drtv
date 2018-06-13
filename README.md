DR TV Grabber
-------------

drtv-grabber modtager video filer fra https://www.dr.dk/tv

Det vælger den fløde som har den højeste bitrate, og det gemmer:

 * en json (metadata) file
 * en jpg (billede) file
 * en mp4 (video) file
 * en vtt (undertekst) file

Man kan bruge drtv-grabber fx,

  "./bin/drtv-grabber SLUG"

med SLUG som identitet af programmet fra URLen, fx

  https://www.dr.dk/tv/se/aftenshowet/aftenshowet-dr1/aftenshowet-2018-06-11#!/00:02

har en SLUG af "aftenshowet-2018-06-11".

Man kan give flere SLUG til sammen.

