.. _Create Exercises:

############################
Creating Exercises and Tools
############################

Studio allows you to create a wide variety of exercises and tools for your course. Many of these exercises and tools have templates in Studio so that you can create them easily. In addition, individual course teams frequently create exercises that don't have templates in Studio. We want to make these tools available to all our course teams as well. 

In this section, we provide you with all the files, code, and instruction that you need to create the following tools and problem types.

Exercises and tools can be created in HTML components, Problem components, and Advanced components. The page for each individual exercise or tool contains step-by-step directions to create that tool. The individual exercise and tool pages also include an example of each exercise or tool.

****************************
General Exercises and Tools
****************************

.. list-table::
   :widths: 25 80

   * - :ref:`Annotation`
     - Annotation problems ask students to respond to questions about a specific block of text. The question appears above the text when the student hovers the mouse over the highlighted text so that students can think about the question as they read.
   * - :ref:`Conditional Module`
     -  
   * - :ref:`Custom JavaScript`
     - Custom JavaScript display and grading problems (also called *custom JavaScript problems* or *JS Input problems*) allow you to create a custom problem or tool that uses JavaScript and then add the problem or tool directly into Studio.
   * - :ref:`Custom Python Evaluated Input`
     - In custom Python-evaluated input (also called "write-your-own-grader problems" problems), the grader uses a Python script that you create and embed in the problem to evaluates a student's response or provide hints. These problems can be any type.
   * - :ref:`External Grader`
     - An external grader is a service that receives student responses to a problem, processes those responses, and returns feedback and a problem grade to the edX platform. You build and deploy an external grader separately from the edX platform. An external grader is particularly useful for software programming courses where students are asked to submit complex code.
   * - :ref:`Google Instant Hangout`
     - You can add the ability for students to participate in instant hangouts directly from your course. With instant hangouts, students cani nteract through live video and voice, share screens and watch videos together, and collaborate on documents. 
   * - :ref:`LTI Component`
     - LTI components allow you to add an external learning application or non-PDF textbook to Studio.
   * - :ref:`Open Response Assessment`
     - In open response assessments, students receive feedback on written responses of varying lengths as well as files, such as computer code or images, that the students upload. Open response assessments include self assessment and peer assessment.
   * - :ref:`Poll`
     - You can run polls in your course so that your students can share opinions on different questions.
   * - :ref:`Problem with Adaptive Hint`
     - A problem with an adaptive hint evaluates a student's response, then gives the student feedback or a hint based on that response so that the student is more likely to answer correctly on the next attempt. These problems can be text input or multiple choice problems.
   * - :ref:`Problem Written in LaTeX`
     - If you have an problem that is already written in LaTeX, you can use this problem type to easily convert your code into XML.
   * - :ref:`Text Input`
     - In text input problems, students enter text into a response field. The response can include numbers, letters, and special characters such as punctuation marks.
   * - :ref:`Word Cloud`
     - Word clouds arrange text that students enter - for example, in response to a question - into a colorful graphic that students can see.

********************************
Image-Based Exercises and Tools
********************************

.. list-table::
   :widths: 25 80

   * - :ref:`Drag and Drop`
     - In drag and drop problems, students respond to a question by dragging text or objects to a specific location on an image.
   * - :ref:`Full Screen Image`
     - The Full Screen Image tool allows a student to enlarge an image in the whole browser window. This is useful when the image contains a large amount of detail and text that is easier to view in context when enlarged.
   * - :ref:`Image Mapped Input`
     - In an image mapped input problem, students click inside a defined area in an image. You define this area by including coordinates in the body of the problem.
   * - :ref:`Zooming Image`
     - Zooming images allow you to enlarge sections of an image so that students can see the section in detail.

************************************
Multiple Choice Exercises and Tools
************************************

.. list-table::
   :widths: 25 80

   * - :ref:`Checkbox`
     - In checkbox problems, the student selects one or more options from a list of possible answers. The student must select all the options that apply to answer the problem correctly.
   * - :ref:`Dropdown`
     - Dropdown problems allow the student to choose from a collection of answer options, presented as a dropdown list. Unlike multiple choice problems, whose answers are always visible directly below the question, dropdown problems don't show answer choices until the student clicks the dropdown arrow.
   * - :ref:`Multiple Choice`
     - In multiple choice problems, students select one option from a list of answer options. Unlike with dropdown problems, whose answer choices don't appear until the student clicks the drop-down arrow, answer choices for multiple choice problems are always visible directly below the question.
   * - :ref:`Multiple Choice and Numerical Input`
     - You can create a problem that combines a multiple choice and numerical input problems. Students not only select a response from options that you provide, but also provide more specific information, if necessary.

********************************
STEM Exercises and Tools
********************************

.. list-table::
   :widths: 25 80

   * - :ref:`Chemical Equation`
     - Chemical equation problems allow the student to enter text that represents a chemical equation into a text box. The grader evaluates the student's response by using a Python script that you create and embed in the problem.
   * - :ref:`Circuit Schematic Builder`
     - In circuit schematic builder problems, students can arrange circuit elements such as voltage sources, capacitors, resistors, and MOSFETs on an interactive grid. They then submit a DC, AC, or transient analysis of their circuit to the system for grading.
   * - :ref:`Gene Explorer`
     - The Gene Explorer (GeneX) simulates the transcription, splicing, processing, and translation of a small hypothetical eukaryotic gene. GeneX allows students to make specific mutations in a gene sequence, and it then calculates and displays the effects of the mutations on the mRNA and protein.
   * - :ref:`Math`
     - (maybe mention that can change text field length, set ci/cs) Numerical input, math expression input
   * - :ref:`Molecule Editor`
     - The molecule editor allows students to draw molecules that follow the rules for covalent bond formation and formal charge, even if the molecules are chemically impossible, are unstable, or do not exist in living systems.
   * - :ref:`Periodic Table`
     - An interactive periodic table of the elements shows detailed information about each element as the student moves the mouse over the element.
   * - :ref:`Protein Builder`
     - The Protex protein builder asks students to create specified protein shapes by stringing together amino acids. In the example below, the goal protein shape is a simple line. 

* :ref:`Numerical Input`: In numerical input problems, students enter numbers or specific and relatively simple mathematical expressions to answer a question. You can specify a margin of error for these problems. You can specify a correct answer either explicitly or by using a Python script.

* :ref:`Math Expression Input`: In math expression input problems, students enter text that represents a mathematical expression into a field, and the LMS changes that text to a symbolic expression that appears below that field. Unlike numerical input problems, which only allow integers and a few select constants, math expression problems can include unknown variables and more complicated symbolic expressions.