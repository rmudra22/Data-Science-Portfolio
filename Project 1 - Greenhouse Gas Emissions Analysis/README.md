# Greenhouse Gas Emissions Analysis in Ukraine (2016-2021)
## Installation

To work with this project, follow these steps:

- Download and Install Anaconda Navigator: Visit the Anaconda website and download the Anaconda distribution suitable for your operating system. Follow the installation instructions provided on the website to install Anaconda Navigator.
- Launch Anaconda Navigator: After installing Anaconda Navigator, launch the application. You can typically find it in your applications menu or by searching for "Anaconda Navigator" in your system's search bar.
- Create or Activate an Environment: Before opening the project, ensure you have created or activated an environment in Anaconda Navigator where you want to work on the project. If you're unsure how to do this, refer to the Anaconda Navigator documentation or tutorials on managing environments.
- Install Required Packages: Once you have your environment set up, ensure that it includes the necessary packages for the project, such as Pandas and Seaborn. You can install these packages directly within Anaconda Navigator. Once you've launched Anaconda Navigator, navigate to the "Environments" tab. Here, you'll see a list of environments along with the packages installed in each one. You can search for specific packages, install new ones, or update existing ones from this interface.
- Launch Jupyter Notebook: In Anaconda Navigator, locate and click on the Jupyter Notebook icon. This will launch the Jupyter Notebook interface in your default web browser.
- Navigate to the Project Directory: Using the file browser interface in Jupyter Notebook, navigate to the directory where you have saved the project files.
- Open the Jupyter Notebook File: Once you've located your project directory, click on the Jupyter Notebook file (with the .ipynb extension) to open it in the Jupyter Notebook editor.
- Run the Notebook Cells: With the Jupyter Notebook file open, you can now execute the cells containing your preprocessing and visualization code by clicking on the cells and pressing Shift + Enter. This will run the code and generate the outputs as specified in the notebook.
- Exploring the Project: Explore the project by interacting with the code, modifying parameters, and observing the results. You can also add your own analysis or visualizations as needed.
- To view the visualizations included in this project, you will need to have PowerBI installed on your system. PowerBI is a powerful data visualization tool developed by Microsoft. You can download it from the official website. Please ensure that you have PowerBI installed before attempting to open the visualization file.

## Gas Compounds Breakdown
It's important to understand a general impact of each of greenhouse gas compound. A little research and a break down here will help us to understand the nature of the missing values in this dataset.

1. **Nitrogen oxides (NO2)** is a reddish-brown, water-soluble trace gas, formed through the oxidation of nitric oxide (NO) in combustion processes.
  - **Key Characteristics:**
     - Influences global climate change by absorbing visible radiation and impacting atmospheric visibility.
     - Plays a critical role in ozone (O3) formation in the troposphere.
     - Controls the build-up and fate of radical species, contributing to oxidative stress in the body.
   - **Sources:**
     - Natural: Lightning, bacterial and volcanic action.
     - Human Activities: Heating, power generation, motor vehicles, explosives, welding, tobacco smoking, use of gas-fired appliances, oil stoves.
   - **Health Impact:**
     - Short-term exposure linked to cardiovascular and respiratory death.
     - Long-term exposure associated with asthma, respiratory infections, and chronic lung disease.
     - Symptoms include coughing, wheezing, difficulty breathing, reduced ability to smell.
   - **Environmental Impact:**
     - Fades and discolors furnishings, reduces visibility, reacts with surfaces.
     - Harmful to vegetation, decreases growth, and reduces crop yields.
     - Contributes to acid rain, forms nitrates causing haze and reducing visibility.

   - **Might be emitted in such categories:**
     - Electricity, gas, steam, and air conditioning supply: NO2 emissions can occur from heating and power generation processes, which fall under this category.
     - Manufacturing: NO2 emissions may occur in various manufacturing processes, particularly those involving combustion, such as welding and the use of explosives.
     - Transport, warehousing, postal, and courier activities: NO2 is emitted from motor vehicles, which are a significant source of NO2 emissions. This category encompasses activities related to transportation.

2. **Sulphur Dioxide (SO2)** - heavy, colourless, poisonous gas with a pungent odor, forming secondary particulate matter (PM2.5) and reacting with ammonia to form ammonium sulphate.
  - **Sources:**
    - Burning fossil fuels for domestic heating, transport, power plants, and industrial facilities.
    - Smelting mineral ores containing sulphur.
    - Natural volcanic activity.
  - **Health Impact:**
    - Irritant affecting lung function, worsening respiratory diseases.
    - Symptoms include eye irritation, wheezing, shortness of breath, aggravated asthma, and chronic bronchitis.
    - Long-term exposure increases hospitalization rates for cardiac diseases and mortality rates.
  - **Environmental Impact:**
    - Forms sulphuric acid contributing to acid rain, which acidifies aquatic ecosystems, damages vegetation, and corrodes buildings.
    - Deprives soil of essential nutrients, leading to deforestation and biodiversity loss.
  - **Ways to Lessen Emissions:**
    - Shift to low-sulphur fuels like natural gas.
    - Install flue gas desulphurization technology.
    - Limit sulphur content in transport fuels.
    - Close older, less-efficient power plants.
   
  - **Might be emitted in such categories:**
    - Electricity, gas, steam, and air conditioning supply: SO2 emissions can occur from power plants and other facilities burning fossil fuels.
    - Manufacturing: SO2 emissions may occur in various manufacturing processes, particularly those involving smelting mineral ores containing sulphur.
    - Transport, warehousing, postal, and courier activities: Although not a direct source, transportation activities may contribute to SO2 emissions indirectly through the burning of fossil fuels in vehicles.

3. **Ammonia (NH3)** - compound of nitrogen and hydrogen, a colourless gas with a pungent odor, forms secondary particulate matter (PM2.5) in the atmosphere.
  - **Sources:**
    - Mainly agricultural processes: fertilizer production, livestock waste management.
    - Indoor sources: cigarette smoke, cleaning solutions, building materials.
  - **Health Impact:**
    - Irritates eyes, nose, throat, and respiratory tract.
    - Large quantities are poisonous, affecting lung function.
    - Associated with reduced lung function, respiratory diseases, heart problems, and lung cancer due to PM2.5 formation.
  - **Environmental Impact:**
    - Contributes to eutrophication and acidification of terrestrial and aquatic ecosystems.
    - Leaching into soil increases acidity, affects plant growth.
    - Toxic to aquatic species, causes overgrowth of algae, affects plant survival.
  - **Ways to Lessen Emissions:**
    - Limit fertilizer applications, cover slurry pits, use tanks for fertilizer production.
    - Prevent water contamination.
    - Plant trees and hedges to absorb gas.
    - Effective monitoring essential for tracking emission levels and assessing measures' success.
  - **Might be emitted in such categories:**
    - Agriculture, Forestry, and Fishing: Ammonia is commonly used in agriculture as a fertilizer. It is also utilized in forestry and fishing activities, such as in aquaculture for water treatment.
    - Manufacturing: Ammonia is an essential chemical in various manufacturing processes, including the production of fertilizers, explosives, plastics, textiles, pharmaceuticals, and cleaning products.
    - Water Supply; Sewerage, Waste Management, and Remediation Activities: Ammonia is used in water treatment processes to remove impurities and adjust pH levels in both potable and wastewater.
    - Additionally, smaller-scale uses of ammonia may occur in categories such as construction (e.g., as a cleaning agent), transportation (e.g., in refrigeration systems), and wholesale and retail trade (e.g., as a cleaning or disinfectant product).

4. **Non-methane Volatile Organic Compounds (NMVOC)** - commonly used as solvents in various industrial and consumer applications, including coating, degreasing, chemical production, printing, and products like lighter fluid and coolant fluid.
  - **Sources and Transportation Pathways:**
    - Emitted during incomplete combustion and vaporization, with past transportation contributing significantly but decreasing due to effective measures. Presently, evaporation from solvents in product use is the major source. Refineries, pulp and paper plants, and natural sources like vegetation also contribute.
  - **Effects on Environment and Health:**
    - Contribute to ground-level ozone formation when combined with nitrogen oxide and sunlight, damaging vegetation and causing respiratory tract irritation in humans.
    - Some NMVOCs, like benzene, are harmful to human health through inhalation, with chronic exposure linked to conditions like leukemia. No recommended safe exposure level currently exists.
Reducing NMVOC emissions requires measures such as improved combustion processes, use of low-VOC products, and adoption of emission control technologies. Monitoring and regulation are crucial for mitigating environmental and health impacts.

  - **Might be emitted in such categories:**
    - Manufacturing: NMVOCs are commonly used as solvents in manufacturing processes, such as coating, painting, gluing, and production of chemical products like rubber, textiles, and adhesives.
    - Construction: NMVOCs can be utilized in construction activities for surface coating, painting, rust protection, and gluing.
    - Wholesale and Retail Trade; Repair of Motor Vehicles and Motorcycles: Products containing NMVOCs, such as paints, adhesives, and cleaning solutions, are sold in retail stores and used for vehicle repair.
    - Information and Telecommunications: NMVOC-containing products like printing inks may be used in the printing industry, which falls under this category.
    - Arts, Entertainment, and Recreation: NMVOCs may be used in arts and crafts materials, such as paints, adhesives, and solvents, utilized in recreational activities.
    - Other Service Activities: NMVOC-containing products may also be used in various other service activities, such as cleaning solutions in janitorial services or printing in printing shops.

5. **Carbon Monoxide (CO)** - a toxic gas that is colorless, odorless, and tasteless. It is produced by the incomplete combustion of carbonaceous fuels like wood, petrol, coal, natural gas, and kerosene.
  - **Sources:**
    - Outdoor sources include vehicle and combustion engines, power plants, biomass burning, forest fires, volcanoes, and BBQs. Indoor sources include incense, boilers, fireplaces, heaters, ovens, cooktops, and tobacco smoke.
  - **Health Impact:**
    - CO inhibits the body's ability to carry oxygen, leading to symptoms ranging from fatigue and chest pain to impaired vision, headaches, weakness, and coma. High concentrations can be fatal, particularly for infants, the elderly, and those with heart and respiratory diseases.
  - **Environmental Impact:**
    - While globally CO has minimal environmental effects, locally it can react with other pollutants to form ground-level ozone or oxidize to form carbon dioxide, contributing to climate change and air quality issues. CO exposure impairs oxygen uptake in both humans and animals.
  - **Reducing Emissions:**
    - Targeting sources of CO emissions is crucial. Indoors, installing detectors and properly venting fuel-burning appliances are key steps. Outdoors, monitoring and controlling emissions from vehicles, power plants, and other combustion sources are essential for reducing CO levels.

  - **Might be emitted in such categories:**
     - Manufacturing: In certain industrial processes, carbon monoxide can be used as a reducing agent in chemical reactions, such as in the production of metal carbonyls, which are used in metal purification and as catalysts in organic synthesis.
     - Mining and Quarrying: In mining, carbon monoxide can be produced inadvertently as a byproduct of certain extraction processes, such as smelting and refining operations. It can also be present in underground mines due to incomplete combustion of fuels used for machinery or explosives.
     - Construction: Carbon monoxide can be emitted from combustion engines used in construction equipment, such as generators, pumps, and vehicles, if not properly maintained or operated in enclosed spaces.
     - Electricity, Gas, Steam, and Air Conditioning Supply: While not directly used, carbon monoxide can be a byproduct of combustion processes in power plants or heating systems powered by fossil fuels.

6.	**Particulate Matter (PM)** - a complex mixture of solids and aerosols composed of small droplets of liquid, dry solid fragments, and solid cores with liquid coatings. PM varies widely in size, shape, and chemical composition, and may contain inorganic ions, metallic compounds, elemental carbon, organic compounds, and compounds from the earth’s crust.
  - **PM is categorized by its diameter -** PM10 (particles ≤ 10 microns) and PM2.5 (particles ≤ 2.5 microns):
     - PM10 includes larger particles from sources like construction, landfills, agriculture, and wildfires.
     - PM2.5 consists of smaller particles from combustion sources like vehicles, power plants, and industrial processes, as well as secondary particles formed from chemical reactions in the atmosphere.
  - **Health Impacts:**
    - Both PM10 and PM2.5 can be inhaled and deposited in the lungs, leading to adverse health effects. Short-term exposure is linked to respiratory issues, hospital admissions, and exacerbation of heart and lung diseases. Long-term exposure is associated with premature mortality, reduced lung function, and increased risk of cardiovascular and respiratory diseases.
  - **Environmental Effects:**
    - PM reduces visibility, affects climate by influencing light absorption and scattering, and can impact ecosystems and materials. It can alter plant growth, soil composition, water quality, and clarity. PM deposition on surfaces can cause soiling and damage.
  - **Indoor Sources:**
    - Indoor PM originates from outdoor sources like pollution infiltration through doors and windows, as well as indoor activities such as smoking, cooking, burning wood, and using cleaning products. Biological sources like pollen, mold spores, dust mites, and indoor activities contribute to indoor PM levels.
  - **Regulation:**
    - Ambient air quality standards set limits on PM levels to protect human health. Standards include annual and 24-hour average limits for PM10 and PM2.5. Regular reviews of scientific evidence inform updates to these standards to reflect current knowledge and understanding of health impacts.

- **Might be emitted in such categories:**
    - Construction: Construction activities such as demolition, excavation, and land clearing can generate particulate matter from dust and debris.
    - Agriculture, Forestry, and Fishing: Agricultural activities such as tilling, harvesting, and processing of crops can generate dust particles. Forestry activities like logging and land clearing can also contribute to particulate matter emissions.
    - Mining and Quarrying: Operations in mining and quarrying industries can produce particulate matter through activities such as blasting, drilling, and transportation of materials.
    - Transport, Warehousing, Postal, and Courier Activities: Vehicles used for transportation and logistics, including trucks, ships, and airplanes, emit particulate matter from exhaust emissions and wear and tear on roads and runways.
    - Manufacturing: Some manufacturing processes, particularly those involving combustion, grinding, or material handling, can generate particulate matter as a byproduct.
    - Electricity, Gas, Steam, and Air Conditioning Supply: Power plants and other facilities that burn fossil fuels for electricity generation or heating can emit particulate matter as a result of combustion.
    - Water Supply, Sewerage, Waste Management, and Remediation Activities: Activities such as waste incineration, landfill operations, and wastewater treatment can generate particulate matter from combustion or mechanical processes. 

7. **Hydrofluorocarbons (HFCs)** are synthetic gases used for cooling, with a short atmospheric lifetime but potent global warming potential.
  - **Key Insights:**
    - They contribute 2% to total greenhouse gases but have a disproportionately high impact on global warming compared to CO2.
    - Climate-friendly alternatives exist, and HFC emissions can be eliminated by 2050.
    - HFCs are entirely human-made, primarily used in refrigeration, air conditioning, foams, and aerosols.
    - Emissions result from equipment wear, maintenance issues, or leakage.
    - HFC commercialization began in the early 1990s, but their atmospheric presence is growing rapidly due to increasing demand, especially in developing countries.
    - Old equipment forms HFC "banks" that release gases until replaced, highlighting the urgency of action.

  - **Might be emitted in such categories:**
    - Manufacturing: HFCs are used in the manufacture of various products, such as insulating foams, aerosol propellants, and fire protection systems.
    - Electricity, gas, steam, and air conditioning supply: HFCs are utilized in refrigeration and air-conditioning systems, which fall under this category.
    - Wholesale and retail trade; repair of motor vehicles and motorcycles: HFC-containing products like air conditioners and refrigerators are sold and repaired within this category.

8. **Sulfur hexafluoride (SF6)** is a synthetic compound used in electric power systems for insulation, interruption, and arc quenching, with an exceptionally high global warming potential.
  - **Key Insights:**
    - SF6 is 23,500 times more effective at trapping infrared radiation than CO2 over a 100-year period, and it has an atmospheric lifetime of 3,200 years.
    - SF6 emissions from electric power systems depend on factors like equipment type, age, and maintenance practices, impacting climate due to its high global warming potential.
    - Strategies to reduce SF6 emissions include leak detection and repair, recycling equipment, and employee education/training.
    - SF6 is used in electrical transmission and distribution equipment, electronics manufacturing, and magnesium production, with electrical equipment being the largest emission source.
    - Despite efforts to prevent emissions, SF6 can escape into the atmosphere during equipment lifecycle stages such as manufacturing, installation, maintenance, and decommissioning.

  - **Might be emitted in such categories:**
    - Manufacturing
    - Electricity, gas, steam, and air conditioning supply

9. **Nitrous oxide (N2O)** is a greenhouse gas, also known as laughing gas, is approximately 300 times more potent than CO2 molecule for molecule and remains in the atmosphere for an average of 114 years. Its emissions, largely from agriculture, comprise roughly 6% of total greenhouse gas emissions.
  - **Sources of N2O Emissions:**
    - N2O emissions stem from various human activities like agriculture, industrial processes, fossil fuel combustion, and waste treatment.
    - Key sources include nitrogen-containing fertilizers, livestock farming, chemical industry operations, and waste incineration.
  - **Climate Impact of N2O:**
    - N2O is a potent greenhouse gas, approximately 300 times more impactful than carbon dioxide in terms of climate change.
    - It has a long atmospheric lifespan of about 121 years, significantly contributing to global warming.
  - **Mitigation Efforts:**
    - Strategies to optimize nitrogen productivity and reduce nitrogen surpluses through improved fertilizer management are crucial for mitigating N2O emissions.
  - **Global Implications and Policy Measures:**
    - The significant impact of N2O on warming the atmosphere underscores the need for global action to address its emissions.
    - International agreements like the Kyoto Protocol mandate reductions in nitrogen emissions, reflecting the global commitment to mitigating climate change.

  - **Might be emitted in such categories:**
    - Agriculture, Forestry, and Fishing: Given that agriculture is a major source of N2O emissions, stakeholders in this sector would benefit from understanding the implications of farming practices on greenhouse gas emissions.
    - Electricity, Gas, Steam, and Air Conditioning Supply: Industries involved in energy production and distribution may find relevance in the discussion of N2O emissions, especially regarding combustion processes and emissions from power plants.
    - Manufacturing: Manufacturing processes, particularly those involving chemical production or emissions from industrial activities, could be affected by regulations or strategies aimed at reducing N2O emissions.
    - Water Supply; Sewerage, Waste Management, and Remediation Activities: The treatment of wastewater is noted as one of the sources of N2O emissions, making this sector relevant for understanding and potentially mitigating such emissions.
    - Wholesale and Retail Trade; Repair of Motor Vehicles and Motorcycles: Industries involved in the distribution and maintenance of agricultural equipment, fertilizers, or products related to emissions management could be impacted by discussions on N2O emissions in agriculture.

10.	**Methane (CH4)** - a primary constituent of natural gas, is a greenhouse gas, and its presence in the atmosphere affects our climate system and the Earth's temperature.
Although CO2 has a longer-lasting effect on our climate, methane has a much higher Global Warming Potential (GWP) than carbon dioxide. Accounts for at least 25% of global warming.
Agriculture and the energy sector are major contributors to methane emissions.
  - **EU Emission Trends:**
    - CH4 emissions decreased by 36% in the EU from 1990 to 2020.
    - Largest reductions in energy supply, waste, and agriculture sectors.
    - Reductions attributed to various factors like decreased agricultural livestock numbers, improved efficiency, and better waste management.
  - **Challenges and Solutions:**
    - Urgent need to prevent and address leaks from oil and natural gas systems.
    - Policy options and technologies available to reduce CH4 emissions, such as landfill gas recovery and biogas production.
  - **Global Perspective:**
    - International cooperation essential to mitigate CH4 emissions and address climate change.
    - EU policies alone insufficient to meet global climate goals, given its share of global emissions.

  - **Might be emitted in such categories:**
    - Agriculture, Forestry, and Fishing: Methane emissions can result from livestock digestion (enteric fermentation) and manure management in agriculture.
    - Energy Sector (Electricity, Gas, Steam, and Air Conditioning Supply): Methane leaks from oil and natural gas systems, including extraction, production, and distribution processes.
    - Waste Management and Remediation Activities: Landfills produce methane during the decomposition of organic waste, and methane can also be emitted from wastewater treatment processes.
    - Manufacturing: Some industrial processes, such as chemical manufacturing, may produce methane emissions as a byproduct.
    - Transport: Incomplete combustion of fuels in transportation vehicles can produce methane emissions.

11.	**Carbon dioxide (CO2)** is a colorless, non-flammable gas present naturally in the atmosphere. It consists of one carbon atom and two oxygen atoms. CO2 plays a crucial role in the Earth's carbon cycle and is a significant heat-trapping (greenhouse) gas.
  - **Natural Sources:** Decomposition, ocean release, respiration, and photosynthesis.
  - **Anthropogenic Sources:** Burning fossil fuels (coal, oil, gas), cement production, deforestation, and land use changes such as agriculture and forestry.
  - **Health Impact:** Exposure to CO2 can lead to various health effects, including headaches, dizziness, difficulty breathing, increased heart rate, and in severe cases, coma or asphyxia.
  - **Environmental Impact:** CO2 emissions contribute to global warming and climate change, leading to rising sea levels, extreme weather events, shifts in wildlife populations, and habitat loss. Urbanization and industrial activities are major contributors to CO2 emissions.

  - **Mitigation Strategies:**
    - Transitioning to low-carbon energy sources and technologies.
    - Improving energy efficiency in sectors like transport and industry.
    - Reducing meat and dairy consumption and promoting sustainable agricultural practices.
    - Combatting local air pollution, which is closely linked to global warming.

