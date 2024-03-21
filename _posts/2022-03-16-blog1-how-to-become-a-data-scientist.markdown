---
title: How to become a Data Scientist
layout: post
date: 2022-03-16 14:25
image: false
headerImage: false
tag:
- jobs
- data science
category: blog
author: manhitv
description: Data Science career
---

[“The sexiest job of the 21st century.”](#https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century), [“The best job in America (2016-2019).”](#https://www.glassdoor.com/List/Best-Jobs-in-America-2019-LST_KQ0,25.htm) Data scientist, a title that didn’t even exist before 2008, is now the position employers can’t hire enough of and job seekers strive to become. There’s good reason for the hype: data science is a hugely growing field, with a median base salary of [more than $100,000 in the United States from 2015](#https://www.glassdoor.com/List/Best-Jobs-in-America-2015-LST_KQ0,25.htm).

<style>
img {
  display: block;
  margin: auto;
}
</style>
<div class="center">
    <img class="image" src="/assets/images/blog1/image_1.png" alt="Alt Text" style="width:70%">
    <figcaption class="caption">Data Scientist - The sexiest job of the 21st century</figcaption>
</div>

This blog was written to help you enter the field of data science. It walks you through the different roles in data science, the required skills and how to get the skills you need. The first part of the blog is designed to help you understand what all these types of data scientists are and how to make the best decisions to start your career, which covers what data science is, what skills it requires and the different types of jobs that share that title. The remainder lays out the different paths a person can take to get the skills needed to be a data scientist and some guidelines on making the best decisions.

---
- [1. Introduction](#1-introduction)
- [2. Skill sets](#2-skill-sets)
    - [2.1. Mathematics/statistics](#21-mathematicsstatistics)
    - [2.2. Databases/programming](#22-databasesprogramming)
    - [2.3. Business understanding](#23-business-understanding)
- [3. Different types of data science jobs](#3-different-types-of-data-science-jobs)
- [4. Learning methods](#4-learning-methods)
    - [4.1. Earning a graduate degree](#41-earning-a-graduate-degree)
    - [4.2. Participating in a data science bootcamp](#42-participating-in-a-data-science-bootcamp)
    - [4.3. Doing data science work in your current job](#43-doing-data-science-work-in-your-current-job)
    - [4.4. Teaching yourself](#44-teaching-yourself)
- [5. Making the choice](#5-making-the-choice)
    - [Skill sets to focus on some specific backgrounds](#skill-sets-to-focus-on-some-specific-backgrounds)
- [6. References](#6-references)

---

## 1. Introduction

So what is Data Science? Data science is the practice of using data to try to understand and solve real-world problems. This concept isn’t exactly new; people have been analyzing sales figures and trends since the invention of the zero. In the past decade, however, we have gained access to exponentially more data than existed before. The advent of computers has assisted in the generation of all that data, but computing is also our only way to process the mounds of information. With computer code, a data scientist can transform or aggregate data, run statistical analyses, or train machine learning models. The output of this code may be a report or dashboard for human consumption, or it could be a machine learning model that will be deployed to run continuously.
To illustrate, if a retail company is having trouble deciding where to put a new store, for example, it may call in a data scientist to do an analysis. The data scientist could look at the historical data of locations where online orders are shipped to understand where customer demand is. They may also combine that customer location data with demographic and income information for those localities from census records. With these datasets, they could find the optimal place for the new store and create a Microsoft PowerPoint presentation to present their recommendation to the company’s vice-president of retail operations.
In another situation, that same retail company may want to increase online order sizes by recommending items to customers while they shop. A data scientist could load the historical web order data and create a machine learning model that, given a set of items currently in the cart, predicts the best item to recommend to the shopper. After creating that model, the data scientist would work with the company’s engineering team so that every time a customer is shopping, the new machine learning model serves up the recommended items.

---

## 2. Skill sets

<div class="side-by-side">
    <div class="toright">
        <img class="image" src="/assets/images/blog1/image_2.png" alt="Alt Text" style="width:80%">
        <figcaption class="caption">Data Science Venn diagram</figcaption>
    </div>
    <div class="toleft">
        <p>If you’ve looked into the different areas of data science, you may be familiar with the popular data science Venn diagram. Data science fell into the intersection of math and statistical knowledge, expertise in a domain and computer science skills (that is, coding). This image is often used as the cornerstone of defining what a data scientist is.</p>
        <p>Although it’s true that all three skills are fundamental and that you need to have each to a degree, you don’t need to be an expert in all of them. The overlap parts show different types of data science specialties. These specialties don’t always map one-to-one with job titles, and even when they do, different companies sometimes call them different things.</p>
    </div>
</div>
Let's dive into each part to find out what these components mean.

#### 2.1. Mathematics/statistics
At the basic level, mathematics and statistics knowledge is data literacy. We break down that literacy into three levels of knowledge:
- <em>Those techniques exist</em>—If you don’t know that something is possible, you can’t use it. If a data scientist was trying to group similar customers, knowing that statistical methods (called clustering) can do this would be the first step.
- <em>How to apply the techniques</em>—Although a data scientist may know about many techniques, they also need to be able to understand the complexities of applying them—not only how to write code to apply the methods, but also how to configure them. If the data scientist wants to use a method such as k-means clustering to group the customers, they would need to understand how to do k-means clustering in a programming language such as R or Python. They would also need to understand how to adjust the parameters of the method, for example, by choosing how many groups to create.
- <em>How to choose which techniques to try</em>—Because so many possible techniques can be used in data science, it’s important for the data scientist to be able to quickly assess whether a technique would work well. In our customer grouping example, even after the data scientist focuses on clustering, they have to consider dozens of different methods and algorithms. Rather than trying each method, they need to be able to rule out methods quickly and focus on just a few.

#### 2.2. Databases/programming
Programming and databases refer to <em>the ability to pull data from company databases and to write clean, efficient, maintainable code</em>. These skills are in many ways similar to what a software developer has to know, except that data scientists have to write code that does open-ended analysis rather than produces a predefined output. Each company’s data stack is unique, so no one set of technical skills is required for a data scientist. But broadly, you’ll need to know how to get data from a database and how to clean, manipulate, summarize, visualize and share data.

<div class="center">
    <img class="image" src="/assets/images/blog1/image_3.png" alt="Alt Text">
    <figcaption class="caption">Python or R is the main language of most data science jobs</figcaption>
</div>

Although most data science analysis is done in R or Python, you’ll often need to use SQL to work with a database to get the data. SQL is the programming language that most databases use to manipulate data within them or to extract it. Consider a data scientist who wants to analyze the hundreds of millions of records of customer orders in a company to forecast how orders per day will change over time. First, they would likely write a SQL query to get the number of orders each day. Then they would take those daily order counts and run a statistical forecast in R or Python. For this reason, SQL is extremely popular in the data science community and it’s difficult to get too far without knowing it.

#### 2.3. Business understanding
A core skill in data science is <em>knowing how to translate a business situation into a data question, find the data answer and finally deliver the business answer</em>. A businessperson might ask, for example, “Why are our customers leaving?” But there’s no “why-are-customers-leaving” Python package that you can import—it’s up to you to deduce how to answer that question with data.
Business understanding is where your data science ideals meet the practicalities of the real world. It’s not enough to want a specific piece of information <em>without knowing how the data is stored and updated</em> at your specific company. If your company is a subscription service, where does the data live? If someone changes their subscription, what happens? Does that subscriber’s row get updated or is another row added to the table? Do you need to work around any errors or inconsistencies in the data? If you don’t know the answers to these questions, you won’t be able to give an accurate answer to a basic question like “How many subscribers did we have on March 2, 2019?”
Business understanding also helps you know what questions to ask. Being asked “What should we do next?” by a stakeholder is a little like being asked “Why do we not have more money?”. This type of question begs more questions. Developing an understanding of the core business (as well as the personalities involved) can help you parse the situation better. You might follow up with “Which product line are you looking for guidance regarding?” or “Would you like to see more participation from a certain sector of our audience?”
Finally, as you become more senior, part of your job is to <em>identify where the business could benefit from data science</em>. With the knowledge of limitations and capabilities of machine learning, experience of solving a variety of data problems as well as which kinds of tasks would benefit from automation, a senior data scientist will be on the lookout for places to implement machine learning to improve exisiting operations.

---

## 3. Different types of data science jobs
You can mix and match the three core skills of data science (covered in the section above) into several jobs, all of which have some justification for having the title data scientist. From our perspective, these skills get mixed together in three main ways: analytics, machine learning and decision science. Each of those areas serves a different purpose for the company and fundamentally delivers a different thing.
When looking for data science jobs, you should <em>pay less attention to the job titles and more to the job descriptions and what you’re asked in the interviews</em>. Look at the backgrounds of people in data science roles, such as what previous jobs they held and what their degrees are. You may find that people who work in similar-sounding jobs have totally different titles or that people who have the same data scientist title do totally different things. Remember that the actual titles used at companies may vary as we talk about different types of data science jobs in this blog.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-5t9h{background-color:#A4C2F4;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-1wig{font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-5t9h"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Name</span></th>
    <th class="tg-5t9h"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Job function</span></th>
    <th class="tg-5t9h"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Typical skills/Tools</span></th>
    <th class="tg-5t9h"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Example tasks</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Data Analyst</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">creates dashboards and reports that deliver data</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Data engineering</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Data visualization</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Storytelling</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Business analysis</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Create an automated dashboard that shows how our number of subscribers is changing over time and lets us filter the data to just subscribers of specific products or in specific geographical regions</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Machine Learning Engineer</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">creates models that get run continuously (in production)</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Data engineering</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- ML/DL modelling</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Deployment, monitoring and maintaining model performance</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">create a machine learning model that can—in real time—predict the probability that a customer on the website will actually finish their order</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Decision scientist</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">creates analyses that produce recommendations</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Mathematical and statistical methods</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Business decision-making</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Able to make a particular analysis</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Communication effectively with stakeholders</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">help the marketing department decide which types of products should be highlighted in the company’s holiday gift guide. The decision scientist might investigate what products have sold well without being featured in the gift guide, talk to the user research team about conducting a survey, and use principles of behavioral science to do an analysis to come up with the optimal items to suggest. The result is likely to be a PowerPoint presentation or report to be shared with product managers, vice presidents, and other businesspeople.</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Business Intelligence Analyst</span></td>
    <td class="tg-0lax" colspan="3"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Similar to Data analyst but use less statistical and programming expertise. Their tool of choice may be Excel instead of Python and they may not ever make statistical models.</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Data Engineer</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">keeping data maintained in databases and ensuring that people can get the data they need</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Data structures and programming</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Advanced data engineering</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Data storage</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- Data governance</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">maintain all the customer records in a large-scale cloud database and manage data from collection to processing to data storage</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Research scientist</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">develops and implements new tools, algorithms, and methodologies, often to be used by other data scientists within the company</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">- PhDs, usually in computer science, statistics, quantitative social science or a related field</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">research and try out methods to get 1% more accuracy on image recognition in self-driving cars or building a new deep learning algorithm</span></td>
  </tr>
</tbody>
</table>

At this point, it’s good to start reflecting on the area of data science you want to specialize in. Where do you already have experience? There are many data scientists who are former engineers, psychology professors, marketing managers, statistics students and social workers. A lot of times, the knowledge you’ve gained in other jobs and academic areas can help you be a better data scientist. If you’re already in data science, it’s helpful to reflect now on which part of the Venn diagram you’re in. Are you happy with it? Do you want to switch to a different type of data science job? Transitioning is often available.

---

## 4. Learning methods
Now that you’ve decided to become a data scientist, you need to acquire the skills! There are many ways to do it, from watching YouTube videos to getting a degree and lots of people will tell you that the way they did it is the only correct path. Worse, it’s easy to feel overwhelmed by the amount you have to learn, such as algorithms, programming languages and statistical methods—and then you throw in the different business domains.
The good news is that there are only four main methods to get the skills you need. Each method has trade-offs in terms of materials taught, the time it takes and the level of self-motivation required, but when you lay them out, it usually becomes clear which is the right approach for you. By the end of this blog, you should understand the different methods and after some reflection, you should be able to decide on the best route for your situation.
The four methods of getting data science skills that I have surveyed are:
- Earning a graduate degree in data science or a related field
- Participating in a data science bootcamp (an 8- to 15-week crash course)
- Doing data science work in your current job
- Teaching yourself through online courses and data science books
Let’s dive into each of these above methods.

#### 4.1. Earning a graduate degree
Many colleges offer graduate degrees in data science, with programs covering a mixture of topics in computer science, statistics and business. Because these programs are master’s degree programs, they generally take two years and cost $10-50,000 USD or more (depending on the specific country). As with most graduate programs, you can choose to go through the program more slowly while having a job and/or potentially take the classes as online courses. Although many schools offer an actual data science degree, depending on your interests, you may choose instead to get a degree in computer science, statistics, business analytics, operations research or something very close to data science.

<div class="center">
    <img class="image" src="/assets/images/blog1/image_5.png" alt="Alt Text">
    <figcaption class="caption">Characteristics of Earning a graduate degree</figcaption>
</div>

Putting it all together, graduate programs in data science are a good fit for people
who want an extensive education and can afford it. A graduate program would allow you to learn all the components of data science at a pace that makes the transition reasonable. Graduate programs are not good for people who already have many of the required skills; the programs are much too long and too expensive to be worthwhile. Also, the teachers aren’t industry experts, so the little new knowledge they impart may not even be very relevant. You may need to get industry experience from internships during your graduate program to augment the degree itself.

#### 4.2. Participating in a data science bootcamp
A bootcamp is an 8- to 15-week intensive course put on by companies. During the bootcamp, you spend more than eight hours every day learning data science skills, listening to industry speakers, and working on projects. At the end of the course, you’ll usually present a capstone project to a room full of people from companies that are looking to hire data scientists. Ideally, your presentation will get you an interview and then a job.
Bootcamps teach you an incredible amount in a very short time, which means that they can be great for people who have most of the skills needed for data science but need a bit more. Sometimes, the best part of a bootcamp isn’t the knowledge itself, but the confidence you get from the program that you can actually do the work.

<div class="center">
    <img class="image" src="/assets/images/blog1/image_6.png" alt="Alt Text">
    <figcaption class="caption">Characteristics of participating a bootcamp</figcaption>
</div>

Bootcamps can be great programs for people who want to switch careers and already know some of the basics of data science. They can also be useful for people who are just leaving school and want to have a few data science projects in their portfolio while they’re in the job market. Bootcamps are not designed to take you from 0 to 60, though; most of them have competitive admissions requirements, and you need to have a background in the fundamentals of programming and statistics to get in and then get the most out of the program.

#### 4.3. Doing data science work in your current job
You may find yourself in a data-science-adjacent job. An unusual, but often very effective method of learning data science is to start doing more and more data science work as part of your current job. Maybe you’re a business-person who adds a business spin to data science reports and could start adding your own graphs. Or maybe you work in finance, making spreadsheets that you could move into R or Python.
Trying to do some data science in your current job is a great method because it’s low-risk and has built-in motivation. You aren’t trying to do an expensive bootcamp or degree program that you have to quit your job for; you’re just trying to add a little data science work where you can. And the fact that you’re doing data science in your own job is motivating because the work you’ll do is valuable to others. Over time, you can do more data science work until eventually, it’s all you do, as opposed to taking an educational program and then suddenly switching jobs.
One important note if you’re taking this path: never become a burden for someone else. Direct burdens might be very obvious, such as repeatedly asking people to create cleaned datasets for you or less obvious, such as continually asking someone to review work you’ve done. You can also create an accidental burden by adding new tools to your team. If you’re in finance, and everyone uses Microsoft Excel except you (you now use R), you’ve just made managing your team more complicated. Be careful as you learn these skills that you aren’t creating issues for other people.
Learning on the job can be an effective way to become a data scientist, provided that you have a job in which you can apply data science skills and people around who can mentor you. If those things align, this route is a great one, but for many, these things are not in place. If you think this route is viable for you, we highly recommend taking it. Jobs don’t often allow for learning on the job, so take the opportunity if you have it.

#### 4.4. Teaching yourself
An enormous number of books cover data science, as well as many online courses. These books and sites promise to teach you the basics of data science as well as the in-depth technical skills through a medium (and at a price point) that is practical. These courses and books—as well as all the data science blogs, tutorials and Stack Overflow answers—can provide enough of a grounding that people can teach themselves data science. These self-driven learning materials are great for picking up individual skills. If you want to understand how to do deep learning, for example, a book can be a great way to do it. Or if you want to get the basics of R and Python, you can take an online course to get started.
If you do decide to go down the self-driven route, it’s important to have some constructive work to do. Again, the best way to get better at data science is to DO data science. Reading books and watching videos is great, but you learn far more from doing your own data science work and learning from that work. Make sure to find a project that you want to do, such as taking a dataset and finding interesting results from it, creating a machine learning model and API or using a neural network to generate text.
Kaggle and DrivenData are great websites for practicing machine learning including open source datasets, multiple solutions to a specific problem, but that’s not all of data science. They miss something which is critical to build a successful career in data science such as asking the right questions, making decisions regarding data sources and metrics to optimize or data munging/wrangling work. The good news is that pet projects can cover all of these!
In conclusion, learning on your own is hard—possible, but hard. You need to be able to figure out the order in which you want to learn things, keep yourself motivated enough to learn the skills and do it all without having a mentor or teacher to help you. You’ll also have a more difficult time displaying your qualifications on a résumé than if you used other methods. This method is the least-recommended way to become a data scientist because of how many things can go wrong and the number of people who don’t succeed in staying focused. If you want to pick up a single skill or technology, taking this route can be more feasible, but learning everything you need to be a data scientist is a hard route.

---

## 5. Making the choice

To choose a path for yourself, take time to reflect on what skills you already have, where your strengths lie and what resources you have.
How do you choose among these four very different avenues to data science? The process is different for everyone, but we propose answering three questions as in the following chart.

<div class="center">
    <img class="image" src="/assets/images/blog1/image_7.png" alt="Alt Text">
    <figcaption class="caption">Questions should be asked when you consider to learn Data Science</figcaption>
</div>

Although these questions should provide you a starting point, you don’t have to make one final decision. You can start by reading books independently, and if you find that you want to go faster, switch to a bootcamp. You can also get a master’s degree in the evening while trying to do data science in your current job. There isn’t one perfect answer; what matters is finding an approach that works for you. If something isn’t working, change it until it does.

#### Skill sets to focus on some specific backgrounds
While we've covered some ideas for making decisions easier above, we can take it a step further to dive into some specific backgrounds close to software engineering.
If you’re still in college, it’s good for you to improve your data structures knowledge and programming skills with SQL, Python or R (or even Java). You also have time to build up a Github or Kaggle profile, which is good to show up your portfolio. You’re ready to work in companies to solve problems.
- If you’re a programmer with more than two years experience, it is better to take online courses, improve knowledge of Deep Learning/Machine Learning libraries and tools. Moreover, you should pick up an area to focus on, such as general Machine Learning, Natural Languange Processing or Image/Video processing. As proposed earlier, the best way to learn data science is to do data science, that’s good for you to practice or do side projects. You’ll have a better option to consider to be a Data Engineer than a Scientist because of similar skill sets with your background. When you become more experienced (for example > 10 years experience), you should focus on solving business problems using data science. Your curiosity helps you to find the problem on your own and solve it yourself. You could also solve more general problems such as scaling challenges with data, and how to benefit from provided sights.
- If you’re Business Analysts, Domain experts or Managers, it’s not necessary to know mathematics or programming, it’s better to take a course to understand how Machine Learning works, their ability and limitation, understand each step in Machine Learning, especially on formulating the business around data.

---

I hope this blog has helped you answer many questions about how to become a data scientist. When you apply for data scientist positions, one thing that I would strongly emphasize is that you need to demonstrate that you can do this job. That can look different for different people. Data science is still a young-enough field that people aren’t sure what it means to be a data scientist and who can be one; it’s still very undefined. There is still a lot of uncertainty in what this role means and the positions are highly paid enough that the perceived risk to a company hiring wrong is very high, so companies are very risk-averse. Companies need to be sure that the candidate can do that job. Some ways I’ve seen people demonstrate that they can do the job is through open source contributions, speaking at local meetups on projects they’ve done and developing a portfolio of projects on a blog or GitHub/Kaggle profile. For me, I took all the MOOCs and books I needed to learn and started a blog about all of these projects. 

## 6. References

[1] <a href="https://www.manning.com/books/build-a-career-in-data-science"> Build a career in Data Science</a>

[2] <a href="https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century"> Data Scientist - The sexiest job of the 21st century</a>

[3] <a href="https://www.glassdoor.com/List/Best-Jobs-in-America-2019-LST_KQ0,25.htm"> Best jobs in America (2016-2019)</a>