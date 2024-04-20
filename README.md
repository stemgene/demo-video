# demo-video
### P1
Hello everyone, I'm Harry, a Data Science and Machine Learning enthusiast.

Many of my friends have told me that they feel confused about setting up their Python working environment and synchronizing their project code with GitHub.

Today, I'll be introducing how to set up a software development environment for Python projects. I'll show you how to collaborate using Anaconda, GitHub, and Visual Studio Code (VSCode).

### P2
Before I introduce these software tools, there are some prerequisites: you need to download and install these three applications. Instead of showing you how to do this, I'll provide the download links and reference videos on this slide. You can also find them listed below this video.

### P3
A reminder for Windows users: You might encounter a situation where, after installing Anaconda or VSCode, you get a "command not recognized" error when trying to use the conda command directly in the Windows command prompt. This happens because you need to add associated parameters to the Windows environment variable settings.

This process might be a bit advanced for Python beginners. If you've downloaded the Anaconda distribution version, you can temporarily ignore this step, as I'll demonstrate how to handle it using the Anaconda prompt.

However, if you're a perfectionist, you can refer to this video to learn how to add parameters to the Windows environment variable.

### P4
Alright, once you've got all the software installed, let's begin with Anaconda.

### P5
Anaconda is a powerful tool for Data Science, Machine Learning, and other Python projects. It contains an IDE and provides management of virtual environments along with the libraries installed in each virtual environment.

### P6
What is the virtual environment and why do we need it?

A virtual environment is a self-contained directory that contains a specific version of Python along with its own set of libraries and dependencies. We use virtual environments to isolate different projects and their dependencies, ensuring that changes made to one project do not affect others.

For beginners in data science who primarily work with Jupyter Notebook and use popular libraries like Pandas, NumPy, and Matplotlib, the need for a virtual environment may not be urgent. This is because these libraries are often pre-installed in the main or base Python environment, making it convenient for simple projects or learning purposes.

### P7

As your Python skills improve and you start working on more diverse projects, you may encounter situations where you want to use different libraries for different projects without causing conflicts. For instance, you might want to use PyTorch for one machine learning project, TensorFlow for another, and showcase your data science projects on an online platform using Streamlit as a third project.

In such cases, installing all related libraries into a single Python environment can lead to library conflicts and make it challenging to manage dependencies. This is where virtual environments come in. They help organize different development environments for different projects. In the image you see, PyTorch, Streamlit, and TensorFlow are installed into separate environments, ensuring a clean and isolated setup for each project.

### P8

OK, let’s jump into the practice operation

First I’ll open the Anaconda prompt, do you remenber I’ve said the anaconda prompt will ignore the environment variable things? That’s why I use anaconda prompt rather than the default windows command prompt

### P9

I’m going to show how to create a repository on GitHub

### P14

If this is your first time connecting with GitHub, an authorization page will launch. Log in to your GitHub account here to authorize the connection.

### P17

Finally, I'll show you how to submit your code to the GitHub repository.

Assuming you've created or edited files in your folder, click the "source control" button to submit them to GitHub. The number displayed indicates how many files have been changed.

Remember, there are two steps to upload your code: commit and push.

### P18

When you're connecting VS Code to GitHub for the first time, you might encounter an issue. Make sure to configure your user.name and user.email in Git.

Click "Open Git Log," then copy these two lines of code one by one. Paste them into the Terminal and replace them with your GitHub username and email.

After that, your VS Code should be able to commit and push files to the GitHub repository.

After pushing the code, you'll see the latest updated files in the repository.

I suggest following these steps to organize your Python projects.

### P19

In this presentation, we've learned how to set up the Python development environment and collaborate using Anaconda, GitHub, and VS Code. We discussed the importance of virtual environments, especially when dealing with multiple projects and libraries to avoid conflicts and manage dependencies effectively. Additionally, we learned how to connect and push code to GitHub from VS Code, ensuring our projects are smoothly integrated into GitHub repositories.

In conclusion, this presentation has equipped us with essential skills for efficient Python project development and management. I encourage everyone to apply this knowledge, organize their Python projects effectively, and enjoy the pleasure of coding!

Happy coding!