---
date: "2023-02-16T20:54:44-03:00"
draft: false
title: "Bringing TensorFlow to Pharo"
slug: "bringing-tensorflow-to-pharo"
description: "A Google Summer of Code 2023 Project Proposal"
tags: ["Smalltalk", "Pharo", "Programming"]
cover:
  image: img/TensorFlowPlugin.jpg
  alt: "A cubic piece of technology with silicon looking parts and a fan intake with hot fluid around it"
---

Pharo is a powerful open-source Smalltalk-based programming language and environment that has been widely used for research and development in various fields. Specially Pharo at [Inria](https://inria.fr), France's National Institute for Research in Digital Science and Technology. However, the lack of a native plugin for [TensorFlow](https://www.tensorflow.org/), a popular open-source machine learning framework, has been a major limitation for high efficiency AI development with Pharo. I've wrote this post to let you know that, I've proposed a Google Summer of Code 2023 project to create a [TensorFlow plugin for Pharo](https://gsoc.pharo.org/tensor-flow-plugin), which will unlock the full potential of Pharo for production grade AI development.

The goal is to create a TensorFlow plugin for [Pharo](https://pharo.org/) that can be used directly by Pharo's C VM, allowing Pharo to take full advantage of the silicon of your graphical processing unit so you have an efficient and powerful way to do mining of that GPU power for any algebra intensive peoject, Machine Learning and AI projects in particular. With this plugin, Pharo will be able to perform AI tasks such as deep learning, neural network training, and image recognition using TensorFlow with no need for additional bridges or third-party libraries that could add significant complexity to any project setup and development and debug process.

The completed project has the ambition to deliver a plugin that provides all the primitives to the TensorFlow API, with at least one unit test to ensure quality assurance. This will enable Pharo developers to use TensorFlow for world class AI development, making Pharo a top-tier platform for machine learning or any synthetic intelligence application.

The project requires basic C programming skills, familiarity with how the Pharo VM is created, basic familiarity with Slang, and strong communication skills. Prior experience in creating a Pharo plugin is preferred.

[Extending the Squeak Virtual Machine](https://rmod-files.lille.inria.fr/FreeBooks/CollectiveNBlueBook/greenberg.pdf) by Andrew C. Greenberg is a great read for getting up to speed on the basics of extending Smalltalk VM functionality.

Together with Sebastian Jordan and Oleksandr Zaitsev from the Pharo community, we'll mentoring the students taking on this project to help them make it real. As a first step in this direction, I've published [How to Create a Pharo Smalltalk Plugin](https://blog.sebastiansastre.co/article/how-to-create-a-pharo-smalltalk-plugin) here to remove any friction of the developing process of Pharo plugins.

Hoping Google likes it and becomes real!

Want to be part of this?

Check the eligibility criteria in [Google Summer of Code 2023: Call for Students](https://gsoc.pharo.org/) and help us make this a new impactful resource for a new reality.

Creating a TensorFlow plugin for Pharo is an important step towards unlocking the full potential of this powerful language for AI development. I believe that this Google Summer of Code 2023 project will be an exciting opportunity for any student who is passionate about machine learning and interested in contributing to an open-source community. With the right skills and guidance, we can make TensorFlow a first-class citizen in the Pharo ecosystem, and enable Pharo developers to take on AI challenges with confidence.
