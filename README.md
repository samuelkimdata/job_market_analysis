# LinkedIn Job Board Analysis
This project was presented during the Demo Day Expo held on March 27th, 2024. 

## Intention
My goal is to provide valuable insights for HR professionals, job seekers, and employers to optimize recruitment strategies and make informed decisions. 

## Dataset
 This dataset was acquired through Kaggle and includes data from June to November of 2023.
 
 Link: https://www.kaggle.com/datasets/arshkon/linkedin-job-postings

## Technologies
1. Python
2. Jupyter Notebook
3. Tableau Public

# Findings
## Salary Analysis
### What is the distribution of median salaries across different industries?

The graph below shows the median salaries based on the pay period, work type, industry name, and remote or on-site work location. 

<img width="989" alt="Screenshot 2024-04-03 at 5 44 44 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/c16b4fd8-ad66-46f1-afbc-bd66764a123a">

This graph can be tailored by the user by making their selections to update the graph. For example, if I were a recruiter in the Software Development industry wanting to know what the median yearly salary is for a full-time remote employee, I can see that the average is $153,466. For full user transparency, this graph includes the total count of salaries that were used to find the total average.

<img width="993" alt="Screenshot 2024-04-03 at 5 45 48 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/1d9c48af-57ba-4f26-a489-811aa58a58f5">


### How do salary levels vary based on job titles within a specific industry? Can we visualize the salary distribution for different work arrangements (e.g., full-time, part-time, contract)?

This graph below allows the user to dive deeper into the salary’s posted for a specific job title within a selected industry. This would provide the user with an overview of compensation rates per industry standard.

<img width="992" alt="Screenshot 2024-04-03 at 5 48 51 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/32348602-b7ab-44ec-964a-4efa4a3d7916">

If I were searching for the average yearly salary for a full-time remote software engineer, I can see that the average is $109,125.

<img width="991" alt="Screenshot 2024-04-03 at 5 49 07 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/b45dd5cb-e405-4c7d-bf09-b032202a719f">

## Company Insights:
### Can we compare the median salaries offered by companies, overall by work type & pay period?

This graph shows the median salary within a specific company, which can be used by employers to get a quick look at their competition’s pay rate for the same job title.

<img width="988" alt="Screenshot 2024-04-03 at 5 57 02 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/48bb9554-d2df-4c81-b2a6-fcd3d1cd7673">

With the same selections as the graph before, we can see the median yearly salary for a full-time remote employee for a specific company, like Blackbaud – a provider of cloud software, data services, and data intelligence, is $138, 531.

<img width="991" alt="Screenshot 2024-04-03 at 5 58 36 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/9c7643ac-fd99-4c9e-ba3c-6d31a012723e">

### How many jobs are remote?

Out of all of the job posts in the dataset, we can see that only about 17% are remote positions.


<img width="980" alt="Screenshot 2024-04-03 at 5 59 09 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/1ff1e861-bdca-4a7a-a75b-1751837ef5e8">

### How many job postings per company are remote vs. on-site?
The company with the most job postings, Insight Global, has a total of 44 remote positions available.

<img width="994" alt="Screenshot 2024-04-03 at 5 59 39 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/2ab341f4-4202-435d-b56f-93388f3e3361">

### Can we visualize the top companies (by employee count) and their number of total job postings? How do the sizes of companies (measured by employee count) correlate with the number of job postings?
If we look at the top companies based on employee counts and see how many jobs have been posted, we can see that even in the top ten, Amazon and Walmart are the top two to post job openings.

<img width="990" alt="Screenshot 2024-04-03 at 6 01 29 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/05087de7-20ba-47bd-a901-1f3d364b1f0b">

## Recruitment Effectiveness:
### What is the ratio of job applications to job views for top companies by employee count?

By splitting the previous graph into remote and on-site work location, then calculating the percentage of applies to views, we can see the average of applications submitted per company. The top companies based on employee count has changed due to some not offering remote work, or some not offering on-site work. 

<img width="997" alt="Screenshot 2024-04-03 at 6 04 46 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/b4444bb3-64e6-453e-964a-7814de1d2d8f">

### Are there differences in application rates between remote and non-remote job postings?

If we look at companies that offer both, like Genesys, we can see that there is a significant increase in views and applies for remote work. As we can see, there is about a 4% increase in remote work applicants than on-site.

<img width="995" alt="Screenshot 2024-04-03 at 6 05 20 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/f19702f2-df04-4c12-8580-52c194189e39">

## Job Posting Trends:
### How have the number of job postings changed over the past year, aggregated by industry?

As we take a look into job posting trends, we can see that there are two visible spikes, one in mid-late august, and another in late-october, early-november. The spike in August can be due to a hiring spree  after the summer season, from reduced business activity to staff vacations, to looking to hire new graduates. The spike in November can be due to a need for more talent before the year ends. In the technology sector, these spikes can possibly be due to new product launches or expansion into new markets that companies are hiring in preparation for those launches. 

<img width="988" alt="Screenshot 2024-04-03 at 6 07 19 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/1d08bb47-7498-4d85-a467-34d0d8089262">

### Which industries have experienced the highest growth in job postings?

We can also see within the period of June to November of 2023, the top industries with the highest growth in job postings are IT Services and IT Counseling, and Hospitals and Healthcare.

<img width="995" alt="Screenshot 2024-04-03 at 6 08 08 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/53ccf590-7697-4ac1-9fc0-4973e3202497">

Recruiters can use this information to see when would be the best time to post job openings, and job-seekers can use this to determine when companies will begin posting.

## Industry Insights:
### What are the top skills in demand for specific industries, and how do they vary?

This graph here details the different job skills required for each industry, filtered by experience level, based on the job posting. For an entry-level applicant, the industries for the most skills required are
- Hospitals and Health Care
- Retail
- Staffing and Recruiting
- IT Services and IT Consulting
- Manufacturing

<img width="996" alt="Screenshot 2024-04-03 at 6 09 55 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/a0cc0cc2-7acf-4bd6-b9e1-ab1b1071cff8">

In the Software Development industry, we can see that Information Technology and Engineering are top skills required to find employment.

<img width="989" alt="Screenshot 2024-04-03 at 6 10 33 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/bda24771-d36b-4ad7-a523-5fd825fd81ae">

This information can be used to determine by job-seekers to see what skills are best to acquire to land a role in a specific industry, and recruiters can use this as a baseline to see which applicants have the most relevant skills according to industry standard.

## Employee Benefits Analysis:
### What types of benefits are most commonly offered by companies, and how do they differ by industry?

Employee benefits are shown to directly contribute to job satisfaction and engagement levels. When individuals feel their employer cares about their physical and mental well-being, they are more motivated to perform at their best.

This graph can be used by recruiters to determine what benefits can be offered to the person hired for the role per industry standard. 

<img width="991" alt="Screenshot 2024-04-03 at 6 11 10 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/9ed9e425-f1cf-46ef-99e8-a1a21edf9e19">

According to this dataset, the leading industry with the most benefits is the Hospitals and Healthcare industry. This next graph allows the user to search for a specific company to understand what benefits are offered. 

<img width="993" alt="Screenshot 2024-04-03 at 6 12 04 PM" src="https://github.com/samuelkimdata/job_market_analysis/assets/135805393/70b715cb-b3eb-4f4a-bc9f-5ff76f9e5b95">

# Conclusion

In conclusion, the analytical tool developed from this LinkedIn job board dataset offers valuable insights for various stakeholders within the job market landscape. 

HR professionals and recruiters can optimize recruitment strategies, benchmark salary and benefits offerings, and understand industry-specific skill demands. 

Job seekers can make informed decisions about opportunities based on salary expectations, in-demand skills, and benefits. 

Employers and executives can refine talent acquisition strategies, identify areas for improvement in benefits offerings and employee satisfaction, and gain insights into industry trends and competitor performance. 

By leveraging these analyses, stakeholders can enhance recruitment processes, attract top talent, and foster a thriving work environment conducive to organizational success.

