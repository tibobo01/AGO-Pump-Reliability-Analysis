# AGO-Pump-Reliability-Analysis
Bridging the Gap Between Engineering &amp; Data Analytics: A Reliability Study on Pump Performance

Can we predict pump failure before it happens?

It is always the job of the field operator to take rounds of running equipment, gathering data and ensuring proper documentation. While it is also worthy to note that a Panel operator is also at liberty to easily sight operating deviations from these equipment, critical values can be missed due to faulty sensors or pressure transmitters.

I created an AGO Pump datasheet (dummy data) to stress on the importance of accurate field rounds as a process engineers. The aim is to conduct a Reliability and Pump Performance Analysis.

By combining chemical engineering principles with data cleaning and visualization techniques, I was able to identify a critical mechanical health issue that could have led to catastrophic failure.

The Workflow;
Data Cleaning (removal of duplicates and alien data) & Imputation: Using Excel, I standardized status labels, removed sensor outliers, and performed Linear Interpolation to maintain trend continuity in the pressure data.
I also calculated the Pump's Dynamic Head.
A Pivot table showing each of the pumps average discharge pressures, flowrate and current (Amps) within a month was also displayed.
Data visualization showing each the pattern of each pumps with their average vibrations, flowrates, discharge pressures and current (Amps)

Recommendation;
From the visualization, it was clear that P-101B is at risk of a mechanical failure (bearing issues or Impeller wear) due to high vibrations. A change-over at this point is very important since the available standby pumps are in good condition.
P-101B needs to be stopped, isolated, drained, purged and handed over for maintenance.
