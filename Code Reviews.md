
# Code Reviews 
## What is a Code Review ? 
Code review is a software quality assurance activity in which source code is viewed and evaluated by one or more individuals. Code reviews take place as a safety measure to prevent errors or upon the completion of a software development feature. At least one reviewer must not be the code's author. Based on static code analysis by peers and automated reviewers, code review is a widely used technique in software development to enhance the quality of software code. Studies show evidence of a decrease in the quantity of defects found after release.
# Code Review Process
- Code is sent by the author for review.
- An automated reviewer analyses and grades code based on factors like complexity, documentation gaps, and failed unit tests.
- After that, the code is given to a group of reviewers who can debate it, ask questions, offer suggestions for each line, and decide which of these two use cases best summarises their comments.

1. The modifications are not feasible to execute
2. The modifications are able to be put into practice.
- A piece of code can be approved for merging into the main branch if it complies with standards and has been examined by every team member.
Article - [Utilising both Objective and Subjective data to examine the efficacy of peer code review in distributed software development](https://jserd.springeropen.com/articles/10.1186/s40411-018-0058-0)
![The code review process](https://browserstack.wpenginepowered.com/wp-content/uploads/2023/09/Code-Review-Process.png)
# Why we Review Code ? 
The following are just a few of the reasons why organisations and individuals ought to incorporate code reviews into their projects.

1. Consistent planning and execution
2. Reducing the impact of your errors
3. Ensuring that the project complies with the specifications
4. Enhancing the efficiency of the code
5. Exchanging novel methods
Code review provides a new pair of eyes to find bugs and basic coding errors before your product moves on to the next stage, which expedites the delivery of software to the customer. It's great to just go over someone's code and point out mistakes. However, there must also be some accountability and follow-up when it comes to the code peer review procedure. Before going into production, make sure there is a procedure in place for checking in again to make sure any code discrepancies have been resolved.

Article - [Reasons why the Code Review Process is Important for Developers](https://www.brightspot.com/cms-resources/technology-insights/5-reasons-why-the-code-review-process-is-critical-for-developers#:~:text=Code%20review%20helps%20give%20a,and%20identifying%20errors%20is%20great)  

# Techniques for Code Reviews
- Less formal: Over-the-shoulder: The developer examines the code while standing behind the author's shoulder. This review is unofficial.
- Pass-around email: For code review, the author emails the code to the reviewers. It is recommended to use this method for open-source projects.
- Pair programming involves two programmers working together on a single machine to write the code. On a single machine, one developer writes the code and another reviews it simultaneously. This method takes a lot of time.
- Tool-Based (More Formal): A small number of specialised tools are used to review the code and offer the ability to interact and offer comments and feedback.

Article - [Code Review Techniques](https://blog.stackademic.com/code-review-software-engineering-bedff59f5a16)


# The main goal of Code Review

Sharing knowledge and learning from one another should be the primary objectives of code review; it should be a two-way process.

This principle actually serves as the foundation for everything else:

Therefore, all of the aforementioned factors have an impact on the quality of the code, which in turn affects the quality of the final product. Sharing information indicates the need for interaction and cooperation, which in turn contributes to team integration.

Article - [Code Review — Danse Macabre](https://medium.com/@father-bart/code-review-danse-macabre-0ae53194fb9e)



# Get to know your team - Code Review

If you get to know your colleagues, it will be much easier for you to recognize their strengths and weaknesses. Three objectives will be achieved by doing this:

provide you with an idea of the types of mistakes, anti-patterns, or omissions they commonly commit.
allow you to understand the fundamental reasons for their behavior.

![alt text](<team.png>)

Article - [A guide to code review](https://medium.com/engineering-at-birdie/a-guide-to-code-review-9a7d39caec37)