# spis15
Labs n Stuff
0 *x** -> E 0
0 *E** -> x 1

#north
1 xE** -> N 1
1 NExx -> W 2
1 NEWx -> S 3
1 NxWx -> E 4
1 xxxx -> E 4
1 xxWx -> E 4
1 Nxxx -> E 4

#west
2 NxxS -> W 2
2 Nxxx -> W 2
2 xxWx -> N 1
2 xxxx -> N 1
2 xx*S -> N 1
2 NxWS -> E 4
2 NxWx -> S 3

#south
3 xxWx -> S 3
3 xEWx -> S 3
3 **x* -> W 2
3 xxWS -> E 4
3 NEWx -> E 4
3 xEWS -> N 1

#east
4 NxxS -> E 4
4 xxxS -> E 4
4 xExx -> S 3
4 Nxxx -> S 3
4 xxxx -> S 3
4 xExS -> N 1
4 NExx -> S 3
4 NExS -> W 2
