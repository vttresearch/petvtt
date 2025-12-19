# PET-VTT

This repository contains Pan-European TIMES-VTT energy system model compiled with The TIMES (The Integrated MARKAL-EFOM System) model generator developed by IEA-ETSAP.
PET-VTT is developed by Technical Research Centre of Finland Ltd and is based on JRC-EU-TIMES by Join Reserach Centre of the European Commission © European Union, 1995-2019, CC BY 4.0., available at https://data.jrc.ec.europa.eu/collection/id-00287 
Changes to the original model have been made: List of changes are introduced at the end of this file, and changes are marked with color coding to the database.

The work was funded by the financial support for the green transition by the European Union (number 151, P5C1I2, NextGenerationEU, project REPower-CEST).

# Authors and acknowledgments

- johanna.markkanen@vtt.fi (admin/main developer)
- tomi.j.lindroos@vtt.fi (admin)
- miika.rama@vtt.fi (manager - energy transition)
- antti.lehtila@vtt.fi (developer)
- julius.kellomaki@vtt.fi (developer - heating)
- tiina.koljonen@vtt.fi (scenarios)
- kati.koponen@vtt.fi (scenarios - carbon dioxide removals)

# License

Creative Commons Attribution 4.0 International
CC BY 4.0 
https://creativecommons.org/licenses/by/4.0/

# Citation

Markkanen J, Lehtilä A, Koponen K, Kellomäki J, Rämä M, Lindroos T, Koljonen T. Pan-European TIMES-VTT Energy system model.

DOI will be added soon.

# Use and more information

Use with VEDA & GAMS. 

- VEDA https://iea-etsap.org/index.php/etsap-tools/data-handling-shells/veda
- GAMS https://www.gams.com/
- TIMES modelling framework https://iea-etsap.org/index.php/etsap-tools/model-generators/times

# List of model updates

Model updates made to the first published version of PET-VTT (until 12/2025):
More detailes of changes will be added soon.

- Lot of bug fixes, introduced in scen-file ZZ_ModelFix.
- Residential and commercial heat energy use calibrated to Eurostat statistics until 2025.
- Heat pump technologies added for district heating.
- Biomass feedstocks (BIOWOO) disaggregated for more detailed division of the Limited feedstock for suitable processes.
- RED III, REFuelEU Aviation and Maritime directives introduced to the model to large extent.
- Includes targets for renewable hydrogen use, RFNBOs and biofuel shares of transport fuels.
- ETS1 and ETS2 WEM/WAM prices updated to match EC's recommendations from 2024.
- Solid sorbent DAC technology added.
- Disaggregation of captured CO2 commodity to fossil (SNKFCO2) and non-fossil components (SNKCO2N).
- CO2 storage annual and cumulative potentials updated.
- Soil carbon sequestration in organic and inorganic soils added.
- Afforestartion and reforestration regional potentials added.
- Biochar soil amemdment process and regional upper potentials added.
- Enhanced rock weathering process and regional potentials added.
- Lot of bug fixes, introduced in scen-file ZZ_ModelFix.
- Transport demands partially updated.
- Added options to replace fossil oil with biofuel or RFNBO in agriculture, buildings. 

For more details, contact johanna.markkanen@vtt.fi or antti.lehtila@vtt.fi


Original model files © European Union, 1995-2019, CC BY 4.0.
