# WeightAPWP
 Matlab code for creating a combined weighted running mean and spline apparent polar wander path

 This repository contains MATLAB scripts to generate apparent polar wander (APW) paths of Gondwana (WeightAPWPgond.m), Laurentia (WeightAPWPlau.m), Baltica (WeightAPWPbalt.m) and Laurussia (WeightAPWPlauru.m).

 Individual paleopoles are listed in an excel file (Paleopoles_Pangea_Formation.xlsx). For instance, Gondwanan poles are shown in Tab "gondwana".

 Results in Table 2 in the manuscript can be produced by running the above scripts which yield output=[1Age 2lonRM 3latRM 4e95a 5e95b 6omega 7Kx 8Ky 9N 10lonSP 11latSP].

 lonRM latRM: location of a running mean pole;
 e95a e95b omega: size and orientation of error ellispse of a running mean pole;
 Kx Ky: precision parameters along the error ellispse axes;
 N: number of input paleopoles used for calculating the running mean pole;
 lonSP latSP: location of a spline pole.

 Please cite our paper:

 Wu, L., Murphy, J.B., Quesada, C., Li, Z-X., Waldron, J.W.F., Williams, S., Pisarevsky, S., Collins, W.J. The amalgamation of Pangea: Paleomagnetic and geological observations revisited. 

