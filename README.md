# Natural-hydrogen-FEM-simulation
Rampart carbon emissions have prompted various countries to adopt a safe and clean environment strategy. In this regard, natural hydrogen plays a vital role in the overall elimination of such emissions. Natural hydrogen is stored deep in shale reservoirs and is generated via different processes which range from Sepertinization, radiolysis, to mention but a few. This file demonstrates how to simulate the natural hydrogen storage, flow, and production in shale reservoirs using the finite element method. The simulation procedure is:
1. Install Comsol (Note that, all the simulations were run on Comsol 6.2)
2. Install Matlab (Matlab 2024a was used)
3. Link Matlab with Comsol (follow the instructions in the Comsol manual)
4. Microscale hydrogen analysis (Open the file, "Kerogen Model.mph"). Note, all the temperature variations, diffusivity, and layer analyses were conducted using this file.
5. Mesoscale analysis (In this section, you first model the natural fractures in Matlab and export them to Comsol for coupling). The Matlab file for generating natural fractures is "". The Matlab file for exporting from Matlab to Comsol is "". The Mesoscale Comsol file is "Model of 40 by 40 m.mph")
6. Macroscale analysis (In this section, Matlab is used to generate the tree-like fractures based on the L-system algorithm. Then exported to Comsol. Within Comsol, the fractures are expanded using the array feature. The Matlab file for the L-system is "". the Matlab file for exporting the tree-like fracture to Comsol is "". The Comsol file for the field model is "Field model_400mby400m")
7. All the graphs were generated in Origin after exporting the data from Comsol as an excel file to Oirgin
8. Enjoy using the file and should you have any question, kindly reach out on marembomicheal@gmail.com.
9. Thank you!
