This is a model of the mammalian olfactory bulb for the
NEURON simulator. The model contains only mitral and
granule cells.

A full description may be found in: 
Davison A.P., Feng J. and Brown D. (2003) Dendrodendritic
inhibition and simulated odor responses in a detailed
olfactory bulb network model. *J. Neurophysiol.* In Press.

It is intended that the properties of the network can be
explored by changing the files parameters_<xxx>.hoc and
experiment_<xxx>.hoc. It should not be necessary to change
the other files.

After compiling the mod files, start the simulation by 
running init.hoc. Type ```show_results()``` if after running the 
odour stimulus simulation the mitral cell spike time 
histogram graph is empty.

For more information, contact andrew.davison@iaf.cnrs-gif.fr

Changelog
---------
2022-05: Updated MOD files to compile with the latest neuron releases where
         ion variables used as STATE can not be declared as GLOBAL.
2024-10: Converted readme to markdown
