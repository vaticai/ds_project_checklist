# Product Manager checklist for managing a Data science project
A Comprehensive primer to manage a Data Science Project responsibly and deliver value with Machine learning.

-----------------------
#### Project Overview Matrix
-----------------------
Quick overview of the project, reasons, cost, timeline, to pursue/not pursue and existing work done.

| Task      | Description |
| ----------- | ----------- |
| What problem are we solving? | One liner elevator pitch on what this project is about |
| Why pursue this project? (Why Now?) | Specific business scenario to execute this project, how does it tie to the mission of the company, cost, savings. |
| What are some reasons to not pursue this? | Few arguments to not pursue this |
| What is the ROI of the project? | Potential cost savings / estimated revenue earned/ human-hours saved/quality improvement/ etc. quantify in a detailed doc |
| What is the timeline for this project in months to productionizing? | Total time in months where you want to go from inception to live in production |
| What is the tentative cost of building and maintaining this? | The total cost of building in terms of engineering and computing resources and ongoing maintenance costs|
| Who will be the end consumer of this ML output? | Eventual consumer of the ML prediction/forecast etc. i.e sales team, a user of the app, etc.|

-----------------------
#### The Stakeholders Matrix
-----------------------
Who are the key builders, managers, and stakeholders for this project?

| Position | Description | Assignment |
| ----------- | ----------- | ----------- |
| Internal Sponsor | Internal sponsor/promoter of this project | __ |
| External Sponsor | External sponsor/promoter of this project | __ |
| EDA, Modeling, Evaluation | ML engineer/ Data scientist who will be responsible for most Modeling related exercises | __ |
| ML Engineer | ML engineer responsible for pipelining, dashboarding, productionalizing AI models | __ |
| Data Engineer | Data engineer responsible for data warehousing, pipelining and productionalizing AI models | __ |
| Product Manager | PM in charge of the usability of the ML model with the business, engineering sprints, road mapping | __ |
| Engineering Managers | Engineering managers in charge of this project | __ |
| Front-end, back-end engineers | Engineers managing either front-end or backend or full stack related to ML | __ |
| DevOps, Security | DevOps specialist and security engineers required | __ |

-----------------------
#### Related work and background
-----------------------
Overview of related work, existing solutions and literature survey.

| Task | Description |
| ----------- | ----------- |
| What are some early validations of this before pursuing this? | Possible indicators that this is wanted by end user|
| Which APIs or cloud solutions provide this? | Are there any solution providers, open-source APIs for this project|
| What are some existing solutions with code? | Are there any solutions on Kaggle/Towards Data science/blogs of starting solutions|
| What are publicly available datasets and competitions similar to this? | Datasets, challenges that can be leveraged|
| Which companies are doing this project? | Are there any companies pursuing this problem|
| Can a rule-based or expert system replace or complement an ML system? | One powerful non ML system that can replace the ML system |
| What is the existing work done? | Top works carried out by DS community/corporates on similar projects, python libraries, etc. or even within the company|

-----------------------
#### ML Requirement Gathering
-----------------------
Requirements for modeling, labeling, latency and data

| Requirement | Description |
| ----------- | ----------- |
| What is the type of ML formulation for this project? | Supervised, Unsupervised, Classification, Regression, Statistical, Object detection, Search, Recommender, Multi-class classification, NLP, Deep Learning, etc.|
| Which data tables are required for this project? | Transactions, Users, table for 12 months |
| How much data is required for this project? | Quantification of data in terms of rows/columns/time/volume/quantity required |
| What is the labeling requirement for this required? | How many labels are needed, are they programmatic or human-generated? |
| What is the labeling cost for this project? | Tentative cost of obtaining labels |
| What will be the internal KPIs to measure the success of this project? | What are some internal KPIs to measure the ML performance, precision/recall |
| What will be the business KPIs to measure the success of this project? | What are some business KPIs to measure the ML performance, click rate, revenue |
| What is the latency for inference the ML model? | Is this a batch or real-time system, if real time, how fast is the prediction? |
| What is the approximate dimensionality of the feature space for this ML model? | Rough estimate on the dimensionality of the vector space |
| Can the ML model be evaluated in an offline setting? | Conditions of evaluating offline, human-evaluation, back-simulation, hold out sets. |
 
-----------------------
#### Roadmap
-----------------------
A detailed roadmap of key milestones and deliverables
 
| Milestone | Description | Date |
| ----------- | ----------- | ----------- |
| Kick-off, executive buy-in |  | 2022-01-01
| Data Acquisition Sample | Acquire a sample size of data to provide feasibility | 2022-01-07
| Exploratory Data Analysis | Perform data analysis, understand machine learning formulation | 2022-01-17
| Preliminary model building and tuning | Transactions, Users, table for 12 months | 2022-02-05
| ML System design | Built the ML training and prediction pipelines | 2022-02-15
| Data integration  | Integrate the ML system with the data pipeline / warehouse | 2022-02-18
| Evaluation pipeline | Offline / Online Evaluation of the machine learning model | 2022-03-01

-----------------------
#### Limitations of ML
-----------------------
Understanding practical limitations and shortcomings of the ML model
  
| Limitation | Description |
| ----------- | ----------- |
| Is there model drift and model retraining frequency? | Will the model lose accuracy over time, does it require periodic retraining |
| What are situations where ML can go rogue? | Situations like unseen data, malfunction, mis-training, label bias etc. |
| Are there any ethical concerns with ML? | Ethical considerations include privacy/surveillance/bias/discrimination/human judgment |
| Are there any privacy concerns with ML? | Does this include anything with privacy and surveillance both implicit or explicit |
| Is there a need to understand the ML decision-making process? | Does the decision making of the AI need to be explained in a detailed fashion |
| Other Limitations of the AI model | Limitations can be Latency, accuracy, out of window samples, time decay |
  
  
<hr>
<!-- Citation -->
To cite this content, please use:

```bibtex
@misc{madewithml,
    author       = {Vatic AI},
    title        = {DS Project Checklist},
    howpublished = {\url{https://github.com/vaticai/ds_project_checklist}},
    year         = {2021}
}
```
