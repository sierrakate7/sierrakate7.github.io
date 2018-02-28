---
layout: post
title:      "Debugging with Pry"
date:       2018-02-28 21:19:52 +0000
permalink:  debugging_with_pry
---

REPL takes the users input, evaluates it, and returns the results to the user. In Ruby, we use the IRB! Whenever we type IRB in our terminal, we are using REPL. Pry is just another form of REPL that you can use in Ruby, but has additional functioning. The IRB is used to enter a brand new environment, while PRY actually lets you get inside your code and is far more flexible than IRB. All you have to do is add 'require pry' at the top of your code and then insert binding.pry anywhere within your code. For me personally, this makes solving issues way easier. 
