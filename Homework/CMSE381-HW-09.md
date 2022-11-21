# Homework 9
## CMSE 381 - Fall 2022
## Due Mon, Nov 28, 2022


### Instructions 


This homework covers two classes. 

- Fri 11/18, we covered 9.2 Support Vector Classifiers
- Monday 11/21, we covered 9.3, 9.4 Support Vector Machines

Problems listed below are from [the textbook](https://www.statlearning.com/). 
- 9.7.2 
- 9.7.8 (Uses the `OJ.csv` data set included in the folder). Do all parts, but notes are below. 
    * (b) Use `C=1` (the default) instead of the book's `cost` information. We don't have a `summary` function so that bit can be skipped.
    * (d) we don't have a `tune` function. Instead, you should use `GridSearchCV` like we used in class. You can use `C = [0.01, 0.1, 1, 10]` in the range. However, we have noticed that particularly for the linear kernel, `GridSearchCV` can be incredibly slow. If you are having issues getting the results to finish, feel free to use a subset of `C` values from above, or set `cv=5` to use fewer splits in the $k$-fold CV. 





### <span style="color: green"> Submit homework to crowdmark, not D2L


You will upload your homework to the crowdmark website. The main changes are:
- You will be emailed a link to the assessment and will upload your solutions to that page. [Here is a link to the Crowdmark help page with information on submitting the homework.](https://crowdmark.com/help/completing-and-submitting-an-assessment/)
- Answers to each question will need to be uploaded separately.  So this will basically require taking portions of the pdf you were generating before and separating them when uploading.  
- Feedback on the homework will be posted via the Crowdmark website 
- Your overall grades will still be visible on D2L when they are posted. 

### Important Reminders

- Homeworks must be typed. Some options for this include word, overleaf/latex, or by including a pdf of a jupyter notebook (not the .ipynb file please!). Some students have had more success in the jupyter case of printing from the browser window.  The "convert to pdf" option requires you to have latex installed. 
- Including figures when explaining your reasoning is highly encouraged.  This can be done as easily as taking a picture of a hand-drawn sketch and including it in your file. Please be sure to include all figures in the main file so we only have to look at one uploaded pdf or document. 
- I strongly encourage collaboration.  In the case that you work with others in the class, please include an acknowledgement section in your homework, mentioning people and resources you used in completing the assignment. While utilizing resources such as the internet and the textbook are encouraged, direct copy-paste is not.  You should always be able to explain any of your solutions to me after the fact. 
- The late homework policy is: 
    - Full credit if submitted on D2L by midnight Friday. 
    - 5% penalty if submitted by midnight Saturday.
    - 15% penalty if submitted by midnight Sunday. 
    - No credit after Sunday. 
    - At the end of the semester, the two lowest homework scores will be dropped. 