# Forbes' 2023 Top Colleges/Universities Endowment Analysis

To more readily identify if Universities are analagous with being a hedge-fund offering classes - as noted of Harvard by Scott Galloway in [this TED talk](https://www.youtube.com/watch?v=qEJ4hkpQW8E&t=336s) - I compiled and analyzed a dataset of 2019-2023 Endowment, First-Time Admittance, and Enrollment rates for [Forbes' 2023 America's Top Colleges list](https://www.forbes.com/top-colleges/), investigating any trends of negative correlation with endowment rates and admittance/enrollment rates. More explicitly, gauging whether an increase in total endowment correlated to a decrease in either first-time undergraduate admissions, total undergraduate enrollment or first-time undergraduate enrollment. Throughout this investigation, I used Python for data exploration, transformation, and visualization. 

*"Top 10 colleges/universities" used in the analysis are comprised of the top 10 colleges/universities listed in Forbes' rankings; however, Columbia University (6th on the list) was excluded throughout EDA due to incomplete data - being replaced by the inclusion of Amherst College (11th on the list). Total endowments were gathered from relative financial sources for each college/university, while the rates of total admissions & enrollment were gathered from a relative Common Data Set (CDS), where available.*

## Interactive Tableau Dashboard
Interactive Tableau dashboard can be found [here](https://public.tableau.com/shared/6TMSMQQ7R?:display_count=n&:origin=viz_share_link). Users can filter by year and college/university, while switching between relative *Admissions* and *Enrollment* dashboards, providing key stakeholders with insights to inform strategic planning by visualizing seasonal trends.

![admissions-dash](https://github.com/user-attachments/assets/2a9236ac-36fe-4a30-96a1-d7ed895b78a9)
![enrollment-dash](https://github.com/user-attachments/assets/c235a1b3-abcf-4497-bb26-5b7bee7dcdc6)

## Summary of Insights
I identified an inverse trend between 2020-2021 endowment growth and admission rates for 70% of institutions - a significant increase in endowment coinciding with a significant decrease in admission rates. There seemed to be few patterns of trends in total endowment vs. undergraduate enrollment and undergraduate admissions. Most notably, 90% of universities saw an increase in endowment through 2019-2021. This trend changed during the following period of 2021-2022, observing that 60% of universities experienced a decrease in total endowment. 

![upenn](https://github.com/user-attachments/assets/d0fc2c66-18a4-4f88-96e6-46178af32b41)
![williams](https://github.com/user-attachments/assets/974647ac-7ebe-465c-a891-c23fcdde7dc8)


## **Recommendations**
Investigating the cause in the 2020-2021 spike for college/university endowment, as well as the observed decreases in admissions for the same period and determine if there is/are any correlation. This may be caused by the first COVID-19 lockdown and the country entering a temporary "primarily-remote" epoch. However, further investigation may lead to trends in endowment allocation and if that possesses any correlation with admission/enrollment rates. The 70% of colleges/universities that experienced an endowment spike would be an advantageous place to begin investigating.

## **College/University Insights**
*Refer to README in Jupyter notebook for relative insights.*

## Contact
Feel free to contact me on [LinkedIn](https://linkedin.com/in/takaris-seales)!
