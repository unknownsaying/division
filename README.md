# division
contains 8 files(Calculation ClosedString5 ClosedString9 OpenString5 OpenString9 worldsheetClosed worldsheetOpen worldsheetRE))

    the numerator is always 10000*(n+2) + 1000*(n+1) + 100*n + 10*(n+1) + (n+2) in 5 digits in OpenString
    the numerator is always 10000*n + 1000*(n+1) + 100*(n+2) + 10*(n+1) + n in 5 digits in ClosedString

    the numerator is always 100000000*(n+2) + 1000000*(n+1) + 10000*n + 100*(n+1) + 1*(n+2) in 9 digits in OpenString
    the numerator is always 100000000*n + 1000000*(n+1) + 10000*(n+2) + 100*(n+1) + 1*n in 9 digits in ClosedString

the denominator is always 10000*n + 1000*n + 100*n + 10*n + n in 5 digits
the denominator is always 100000000*n + 10000000*n + 1000000*n + 100000*n + 10000*n + 1000*n + 100*n + 10*n + n in 9 digits

btw worldsheetClosed + worldsheetOpen = worldsheetRE

One more Thing : numerator is upper , denominator is lower (don' turn updown)

