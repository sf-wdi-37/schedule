# Week 8

The evening trainings and readings below will help you solidify work so far and/or prepare you for the next day's materials.


### Monday

link to submit on [tonight's pulse check](https://docs.google.com/forms/d/e/1FAIpQLScicQdZtf2JLFw4O-u618YhNeaJ7sJXVN36ybzO7pnaV359QA/viewform?usp=sf_link): none

1. Connect your local git repository to a remote repository on GitHub.  (Follow [GitHub's instructions](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) to do this!) Push your in-class work to GitHub. If you were working with someone else driving, copy and paste their code from GitHub into your file to continue work after you separate. List collaborator names at the top of your file. 

2. Spend about 30 minutes to an hour working on the following [exercises from the ruby methods notes](https://github.com/sf-wdi-37/ruby-methods/blob/master/exercises.md):

- Looping 1-3 (stretch: add 4-5)
- Array#map 1 (stretch: add 2)
- Methods 1-2
- (stretch: add Enumerable#inject 1-2)

> As you go, practice the [strategies we brainstormed](https://github.com/sf-wdi-37/ruby-methods/blob/master/strategy.md). 

> Commit after you finish each method. Push your work to your GitHub repository when you finish. 

> Save some time to look over [example solutions](https://github.com/sf-wdi-37/ruby-methods/blob/master/example-solutions.rb).

3. Work through this [OOP reading](https://github.com/sf-wdi-37/ruby-oop-reading).  It will probably take 1-2 hours. Write down answers to each of the [reflection questions](https://github.com/sf-wdi-37/ruby-oop-reading#reflection-questions) from the bottom of the readme, and **bring your answers in with you tomorrow.**  Tips:
  * If you just read through this, you're not getting the full benefit!  Instead, create a Ruby file to follow along with the code examples and run it every step or two with `ruby your_file_name.rb`.  
  * Try things out! Would it break if I do `car[color]`?  
  * If you're not feeling cars, create an entirely different class following the same examples (plants? phones? baseball players?)!  **Following along in code is a great strategy for reading docs on unfamiliar topics!**  
  * If you want to split this longer reading up a little, good break points are before "Inheritance" and before "Modules".
  


### Tuesday

link to submit on [tonight's pulse check](https://docs.google.com/forms/d/e/1FAIpQLScicQdZtf2JLFw4O-u618YhNeaJ7sJXVN36ybzO7pnaV359QA/viewform?usp=sf_link): none

1. Finish challenges 1-6 in part 1 and challenge 15 from part 2 of [Ruby Monster OOP lab](https://github.com/sf-wdi-37/ruby-monster-oop), then look through the [solutions](https://github.com/sf-wdi-37/ruby-monster-oop/blob/master/solutions/monster.rb) for at least 10 minutes. 

2. Read through the [test code from Ruby Methods Drills](https://github.com/sf-wdi-37/ruby-method-drills/tree/master/spec). Using that example, some [documentation for the basic structure of an rspec test](https://www.relishapp.com/rspec/rspec-core/v/3-5/docs/example-groups/basic-structure-describe-it), and the structure of [expectations](http://www.relishapp.com/rspec/rspec-expectations/docs), come up with basic explanations for the following Rspec methods:  `describe`, `context`, `it`, `expect`.  This should take about 30 minutes. 

3. Choose an item you are familiar with - like a jacket, table, mobile phone, etc.  Pseudocode tests for a Ruby class based on that object. Write down 5 "expect" lines for the object. This should take about 10-20 minutes. An example might be:

 ```
 describe Backpack
    it stores an array of a backpack's contents
      - expect a new backpack instance to have an empty array for contents
    it has a color that doesn't change
      - expect to be able to get the color
      - expect not to be able to set the color (get an error, or something)
    it has a method to let us add items one at a time
      - expect the method to take in an item
      - expect the method to add that item into the backpack's content array
 ```
 
 4. Use any extra time to continue working on Ruby method drills.



### Wednesday

link to submit on [tonight's pulse check](https://docs.google.com/forms/d/e/1FAIpQLScicQdZtf2JLFw4O-u618YhNeaJ7sJXVN36ybzO7pnaV359QA/viewform?usp=sf_link): your [Ruby Method Drills](https://github.com/sf-wdi-37/ruby-method-drills)  repository

1. Continue working on the [Go Fish](https://github.com/sf-wdi-37/go-fish-card-game) lab for about **one hour**. Remember to read the test output carefully!! Reference the solutions if you get stuck.

2. Tomorrow we begin using Ruby on Rails, a Ruby framework that will help us develop web applications!  First, check out [the Rails home page](http://guides.rubyonrails.org/getting_started.html). Spend **10 minutes** reading the home page and clicking through the links in the nav bar and seeing where each goes.  

3. As a new Rails developer, you'll spend a lot of time with the [Rails **API** documentation](http://api.rubyonrails.org/).  Read the "Welcome to Rails" section of the documentation home page. (Hold off on Getting Started, we'll do that next! This should take around **15-30 minutes.**) Pay special attention to the following question:
  * What's the big deal about Models, Views, and Controllers?
  <br>

4. You should also take advantage of Rails's wonderful [**Guides**](http://guides.rubyonrails.org/). Please read and follow along with chapters 1-4 of the [Rails getting started guide](http://guides.rubyonrails.org/getting_started.html). This should take about **an hour** including the steps below. Pay special attention to the following questions:
  * What are the guiding principles of Ruby on Rails?
  * What does the terminal command `rails new blog` do?
  * Spend 10-15 minutes exploring the directories and files Rails creates for you! For example, what do you think `app/views/layouts/application.html.erb` is doing for the project? How about `Gemfile`?


### Thursday

link to submit on [tonight's pulse check](https://docs.google.com/forms/d/e/1FAIpQLScicQdZtf2JLFw4O-u618YhNeaJ7sJXVN36ybzO7pnaV359QA/viewform?usp=sf_link): your Go Fish Lab

1. Work through part of the Rails getting started guide, according to [this training](https://github.com/sf-wdi-37/rails-guides-training/blob/master/README.md). Doing the whole guide would probably take **5-6 hours**. **Don't do the whole thing!** Cap yourself at 2 hours.


<!--
### Weekend

link to submit on [tonight's pulse check](https://docs.google.com/forms/d/e/1FAIpQLScicQdZtf2JLFw4O-u618YhNeaJ7sJXVN36ybzO7pnaV359QA/viewform?usp=sf_link): your Rails Getting Started Guide work (if you don't have a GitHub repo for your work yet, follow [GitHub's guide](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) to create one)

1. Complete the [Rails Bog App](https://github.com/SF-WDI-LABS/rails_bog_app) four times, according to the [Workflow instructions](https://github.com/SF-WDI-LABS/rails_bog_app/blob/master/README.md#workflow). Don't forget to create a new branch for each run and start on a `first-run` branch. The weekend will be more complex if you accidentally change your `master`.  This will take a significant amount of time. Plan for at least 10 hours.

2. Read chapters 1-2 of the Rails Guide on [Migrations](http://guides.rubyonrails.org/active_record_migrations.html). Write down 2 important term definitions you learned and 2 situations where you think you'll use migrations.

3. Read Chapter 1 (Why Associations?) from the [Active Record Associations Rails Guide](http://guides.rubyonrails.org/association_basics.html).  Then, skim through the following sections:
  - 2.1 The `belongs_to` Association
  - 2.3 The `has_many` Association
  - 2.4 The `has_many :through` Association
  - 2.10 Self Joins

-->

## Outcomes Homework 
#### Due Wednesday 5/31

Research 3-5 websites you like and note the design **AND BRAND** for ideas towards your portfolios. Do not mix designs if they don't go well together, notice also the aesthetic that brings the design elements together. Pair up with a UX Design student as needed for feedback and ideas towards designing your portfolio. 
