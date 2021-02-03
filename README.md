<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

Meal creator

## Summary

The goal of the project is to produce new dishes customized for each person's preferences. The dishes should be balanced from a nutrition and health standpoint. It would use a combination of AI technologies to produce dishes.

## Background

* Which problems does your idea solve? The idea is meant to guide a person into eating healthy and according to their preference, and to discover new dishes. 
* How common or frequent is this problem? This is a daily problem, as people need to eat everyday, and eating healthy is a current important concern. 
* What is your personal motivation? My personal motivation behind this project is that I love all kind of food, and do not eat very healthy. 
* Why is this topic important or interesting? I think this project could help people decide what to eat and discover new "person-tailored" food combination recipes.

## How is it used?

The application is meant to work continously, learning from the person's preferences everyday. This solution can be used everyday in the context of cooking at home at any time of day for meals. The user of this application is anyone who wishes to eat something new and that the application recommends based on his/her own preferences. It is important that the user inputs the preferences and marks ingredients and/or dishes that he/she likes or doesn't.

<!-- Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg) -->

<!-- If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300"> -->

## Data sources and AI methods

The data should be collected on a daily and ongoing basis from the user of the application. The data amount grows and improves the performance of the application gradually. It is collected by inputting preferences and rating the new dishes proposed by the application. Therefore, the data would be formatted as ingredients and combinations of them. Some cooking processes should also be considered in the data and have associated "health values" and "preference values".

Concerning AI methods, for the generation of new dishes, I think Artificial Neural Networks would be helpful to produce entirely new dishes (Generative Adversarial Networks) and/or variations (Variational AutoEncoders). The process of making the ingredients into a dish can be simulated by a Feed-forward Neural Network or a Convolutional Neural Network. Also, since Neural Networks use vectorized representations to operate, recommendation algorithms can be directly used. Some illustrations of main idea for the project are shown below.

![Top level architecture](https://github.com/tinthebear/BuildingAIProject/TLArch.png)

## Challenges

The project is not a large database of cooking recipes. The idea is to produce new, healthy and tasty dishes based on previous experience, but it does not teach a person how to cook. I think the limitations are that the application would not work right away, since it needs to "get to know" the user. Other considerations to take into account, perhaps include some more constraints, such as religious or regional restrictions. 

## What next?

I see that the major challenge is in "combining" the ingredients into a dish. However, I see that the generative architectures and recommendation functionalities should not be that complicated to integrate. I am a novice in implementing Neural Networks, so I would have to study more, and practice more implementation.

## Acknowledgments

* Thermomix
* Great cooks (such as Gastón Acurio)
