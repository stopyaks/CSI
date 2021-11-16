CSILimnologyToolbox
===================

ArcGIS toolbox for limnology.

This toolbox is for ArcGIS and was created with and for version 10.1. It won't work with any previous version of ArcGIS.
It might work with any version 10.x but that has not been tested.
It also requires Spatial Analyst for some tools and Rivex for an input (rivers with Strahler) to the Lake Order Tool.
These are legacy tools from a project where watersheds and lakesheds were created and attributed for the entire northeast and midwestern US.
Most were created to produce a one-time mass run of terrain analysis and lake attribution. Thus, error handling and such are typically minimal.
While some steps in the analysis were conducted in MSU's supercomputing environment (ie Taudem
pitremove & d8flowdir were ported to RHEL to get the data processed faster), you can do these steps on a workstation
easily enough with ESRI's tools or with Taudem toolbox or command line tools. 

Taudem tools are available at:
http://hydrology.usu.edu/taudem/taudem5.0/downloads.html
Special thanks to Dr. David Tarboton and his team for creating these and sharing them.

*This toolbox was designed for a specific version of the NHD schema that was in production circa 2015. The current NHD schema is different so some modification of
the scripts would be necessary to run them against the latest NHD releases.

The CSI Limnology Toolbox comes without guarantees of any kind. We just put it on Git because we like to share. 
The toolbox is unsupported but feel free to direct questions to me, Scott Stopyak: stopyak.scott@gmail.com

Enjoy.
