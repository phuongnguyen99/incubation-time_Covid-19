# incubation-time_Covid-19
This project is about to access the risk factors for the incubation time of COVID-19.
COVID-19 is the global pandemic which infected more than hundred millions of people, killed more than 3.6 people all over the world
(https://coronavirus.jhu.edu/map.html). So knowing the incuabtion time (the time from infection to symptom onset) of this disease can help prevent people from infecting. In other words, knowlege of incubation time helps control the pandemic and set up proper quarantine procedures. 
The goal is to evaluate incubation time of some variables (those are age and gender) with the incubation time of COVID-19. And the findings could provide some guidance on shortening or lengthening the standard quarantine duration of 14 days for certain subgroups and help better control the pandemic

We develop three methods for regression analysis of the incubation period of COVID-19 under the Cox proportional hazards model in order to account for the unobserved and truncated infection time and the censored symptom onset time. The first method is midpoint imputation. The second one is to treat the incubation time as interval-censored. And lastly, the multiple imputations for the infection time based on non-parametric maximum likelihood estimation(NPMLE), uniform distribution and the exponential epidemic growth.
