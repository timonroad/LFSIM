# LFSIM
Simple fish population length-frequency generator, with some stochasticity, to illustrate effects of varying growth parameters on shape of length-frequency distribution of a model population

Coded in Microsoft Visual Basic 5 in 2010 for a training exercise for the Nauru Fisheries and Marine Resources Authority.

This example takes 14 annual cohorts with up to a million fish, each fish with Von Bertalanffy growth parameters K and L-infinity, where both of these parameters are allowed to vary around a fixed mean according to set standard deviations from those means. 

Different mortality rates can be applied to each year-class. The length of each fish is calculated according to its individual growth parameters and age, mortality is applied, and the resultant length-frequency histogram plotted.

Primitive, but it was useful at the time.

LFSIM2_VB.TXT is the VB source code and LFSIM2.EXE is a compiled standalone version that runs under Windows. 
