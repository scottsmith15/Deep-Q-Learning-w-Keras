## Beginning Maze:
![image](https://user-images.githubusercontent.com/82340486/155406355-024cb9ea-e562-42b1-bd11-2f5299f343fb.png)

## Maze Solution:
![image](https://user-images.githubusercontent.com/82340486/155406178-a4287802-c607-4c59-9d2f-f057c6e11fc0.png)



# Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
For this project, I’ve implemented a deep Q-learning algorithm that is used by an intelligent agent to navigate a maze.  Environment code has been provided, which includes the maze represented as a matrix.  Game experience code has also been provided, which is used by the algorithm to store episodes and accessed later as experience replays.  Additional code draws the maze on the screen, which helps us visualize the path the intelligent agent takes to solve the puzzle.  

I was given a pseudocode Q-learning implementation and defined all the specifics required to develop a successful algorithm for this application.  My deep Q-learning algorithm trains itself by engaging in a series of epochs consisting of many episodes, in which the intelligent agent randomly selects a space in the maze, chooses between a random action (exploration) or a predicted action (exploitation).  All episodic information is stored as experience replays and is used to enhance the training model.  After a series of many epochs, the agent will learn how to successfully complete the maze from any position using this value-based algorithm.  At this point, the training is finished, and the agent’s performance is verified by playing (and winning) a new instance of the game.    

# Connect your learning from throughout this course to the larger field of computer science:
# What do computer scientists do and why does it matter?
As humans, we have become increasingly reliant on technology for many activities and tasks.  Artificial intelligence (AI), put simply, is the advancement of this basic application to facilitate the completion of very complex tasks, tasks that may otherwise be impossible for humans.  Advances in AI have shown levels of performance that outdo the capabilities of humans.  As computer scientists, we are building our future through these advanced technologies.  They can assist us in accumulating greater knowledge and allow us to develop a better understanding of ourselves and the universe.       

# How do I approach a problem as a computer scientist?
Computer science problems can be very complex and have many layers.  Thankfully, we have robust technologies at our disposal to assist us in completing tasks in a rapid manner.  It is important to digest the requirements of a problem scenario completely before implementation.  Planning and an initial design phase are integral to avoiding common pitfalls during development.  When it comes time to implement solutions, I find it best to use a divide and conquer approach.  By breaking problems down into small, manageable tasks, we can more easily integrate individual components at a later point in development.  I personally find it helpful to achieve clarity on specific features and components before moving on during a project.  This prevents the occurrence of additional complexities and issues later.   

# What are my ethical responsibilities to the end user and the organization?
Computer science applications and solutions are developed entirely for the benefit of the user.  When working with AI, we are entering a field that impacts our society at large.  We are subverting the control of processes from human to machine, and this requires a great level of attention to detail and understanding.  As a result, AI systems can potentially introduce unwanted bias, which can have lasting negative effects on users and organizations.  As we begin to implement solutions for problems that dwell in areas of understanding beyond human capacity, we must keep an awareness toward these implications, and we hold an even greater responsibility for the later impacts of our intelligent systems.  Research should be performed responsibly and cautiously as we begin to incorporate AI into our daily lives.  In doing so, we may safely invent what could be the most significant and hopeful advancement for humanity in the modern age.
