# Java Getting Started

The goal of this exercise is to transition from a Node stack into a Java stack. In our Node stack we have been using React for the front-end framework and we could use that in Java as well but what we are gonna take a look at is something called HTML Templating. Node has it's own HTML Templating such as [Pug](https://pugjs.org/api/getting-started.html) and we'll take a look at the equivalent for Java in this exercise.

> NOTE: Best to **NOT** fork this repo but instead use it as instructions and create your own repo. You will be specifically prompted to do this at the appropriate time in the below instructions.

## Exercise Instructions

### 1.0 - Transitioning Stacks

It is not uncommon as a Software Engineer to be asked to move to a new / different stack. Equally as important as physically being able to transition to a new stack is our willingness as Software Engineers to head off into a language or way of doing things that we're not familiar with. To get a look at how we're gonna approach this transition take a look at the video linked below.

**Video:**
[Transitioning Stacks to Java](https://vimeo.com/492086703)

Try googling the questions posed in the video to get an idea for all of the Java options out there before moving on. Move onto the next step ([2.0 - Installation](/#2.0 - Installation)) only after you have allowed yourself some time researching the new stack.

### 2.0 - Installation

We have 2 new things that we need to get installed on our machines before we can jump into code. The first thing is the actual Java language, just like when we installed Node.js. The second thing is going to be an IDE / Editor that is meant for working with Java. For the IDE / Editor we are going to go with Intellij. For Intellij make sure you are downloading the Community version, the Ultimate version is not free.

- [Downloading Java](https://adoptopenjdk.net/)
- [Downloading Intelij](https://www.jetbrains.com/idea/download/#section=mac)
- [Installation Walkthrough Video](https://vimeo.com/493430338)

#### 2.1 - Installing Java

[Java Installation](https://vimeo.com/493430338)

**Update Brew:**

> NOTE: If you cannot remember the last time you installed something using **brew** then make sure to follow this process to update **homebrew**.

1. `brew update`
    1. You might be prompted to run the following git command because of some recent updates ti Git and Brew.
    1. `git -C /usr/local/Homebrew/Library/Taps/homebrew/homebrew-core fetch --unshallow`
1. `brew tap homebrew/cask-versions`
1. `brew tap homebrew/cask`

**Installing Java:**

1. `brew tap adoptopenjdk/openjdk`
1. `brew install --cask adoptopenjdk`
1. `java --version`
    1. Test to verify that the the Java language has been install on your machine.

#### 2.2 - Installing Intellij

[Code Editor Installation Video](https://vimeo.com/493430338#t=7m3s)

1. navigate to [Intellij Download](https://www.jetbrains.com/idea/download/#section=mac)
1. click on the Download button for the **Community** version
    1. at the bottom of the browser you should see the downloaded `.dmg` file
    1. click on the arrow and select the show in finder option
    1. double click on the `.dmg` file
    1. drag Intellij app into the Application folder as prompted
1. after download is complete find Intellij in the Application folder
1. double click to open the IntelliJ application
1. pin the application to the MacOS Dock
    1. right click on the Intellij icon in the MacOS Dock
    1. go to **Options**
    1. click on **Keep In Dock**
