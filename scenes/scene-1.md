# Config
 - Title: Downtime - again?!
 - Image: http://res.cloudinary.com/triggerz/image/upload/v1513594352/Billede1_ls6myi.png

# Description

You are an new Associate manager and have since your started several months ago worked hard  - and most days also long hours - to succeed. An SPS (systematic problem solving) has been conducted on the production line at one of the stations in cell 4. It's about a problem that has occured many times and force the line to stop each time.The technicians are fairly sure they have found the solution. They need to stop the line the implement the solution. Your production line is barely reaching its production target and management is pushing for as much production as possible. And luckily the line is running without any problems at the moment. Furthermore, over recent weeks your Department Manager has been asking you to solve more issues on your own and not consult her about smaller issues. So, how do you solve this production line issue?

# Choice
You consult your Department Manger and ask for downtime to fix the production issue once and for all.

# Variables
 - Resources: -1
 - Engagement: -1
 - Output: +3
 - Total: round(((Engagement * Output) / 100) - (100 - Resources))

# Feedback
Even though your Department Manager has asked you to fix smaller things on your own initiative, this is an issue that requires your manager's involvement. With the pressure of reaching production targets, this might not seem the easiest solution - but it is the right one in the long run. Good choice.

# Choice
You stop the SPS and argue that there is no time to fix the production line issue at the moment, due to production targets that need to be met. The line is running at the moment, so you take the chance and hope it will continue working. 

# Variables
 - Resources: -1
 - Engagement: -2
 - Output: +3
 - Total: round(((Engagement * Output) / 100) - (100 - Resources))

# Feedback
This might seem the easiest solution - why fix something that's not broken? But it is broken - even though it works right now. Hoping it will continue like that is not a sustainable way of doing it. You should take the necessary time to fix the production line issue as it keeps the line running in the long run. 

# Choice
You continue the SPS, but argue that the problem must be fixed without shutting down the production line. 

# Variables
 - Resources: -3
 - Engagement: -3
 - Output: +3
 - Total: round(((Engagement * Output) / 100) - (100 - Resources))

# Feedback
This is not an optimal solution as you are asking the technicians to compromise the quality of their work. It will demotivate them and the solution they find will not be tested properly so you may end up not solving the problem after all. That's not a sustainable way of doing it. Cutting corners is not the way forward here. 

# Choice
You know the production line closes at 20:00 tonight, and you could come by and test the issue yourself later that evening.

# Variables
 - Resources: +0
 - Engagement: -3
 - Output: -3
 - Total: round(((Engagement * Output) / 100) - (100 - Resources))

# Feedback
You are a dedicated employee! This option would save on downtime and make sure you can reach your production target. However, you have already been working too much for a long period of time and returning to work after hours just adds to you already unhealthy work-life balance. 


