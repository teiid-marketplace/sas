SasServer
=========

A Translator for SAS Server


To build run

mvn clean install -Dteiid.version=8.4.1 -Dsas.version=9.2

note you have to provide the SAS jar files in your local maven repository for above to work

TODO:
1) Add Function support for 

 addr
 arsin
 atan
 band
 betainv
 blshift
 bnot
 bor
 brshift
 bxor

 byte
 ceil
 cinv
 collate
 compbl
 compound
 compress
 cos
 cosh
 css
 cv

 daccdb
 daccdbsl
 daccsl
 daccsyd
 dacctab
 date
 datejul
 datepart
 datetime

 day
 dcss
 depdb
 depdbsl
 depsl
 depsyd
 deptab
 dequote
 dhms
 digamma
 dmax

 dmean
 dmin
 drange
 dstd
 dstderr
 dsum
 duss
 dvar
 erf
 erfc
 exp
 finv

 fipname
 fipnamel
 fipstate
 floor
 fnonmiss
 fuzz
 gaminv
 gamma
 hms
 hour

 int
 intck
 intnx
 intrr
 irr
 ispexec
 isplink
 kurtosis
 left
 length
 lgamma

 log
 log10
 log2
 lowcase
 max
 mdy
 mean
 min
 minute
 mod
 month
 mort
 n

 netpv
 nmiss
 npv
 ordinal
 poisson
 probbeta
 probbnml
 probchi
 probf
 probgam

 probhypr
 probit
 probnegb
 probnorm
 probt
 qtr
 quote
 range
 ranuni
 rank

 recip
 repeat
 reverse
 right
 round
 saving
 second
 sign
 signum
 sin
 sinh

 skewness
 sqrt
 std
 stderr
 stfips
 stname
 stnamel
 substr
 sum
 tan
 tanh

 time
 timepart
 tinv
 today
 tranwrd
 trigamma
 trim
 upcase
 uss
 var
 weekday

 year
 zipfips
 zipname
 zipnamel
 zipstate
 
 
 2) The driver seems very sensitive and does not give lot of error information
 
 3) capabilities needs to be carefully vetted
 
 4) testing
