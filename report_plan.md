# Draft: Report Group ...

## Focus: ... cancer

## Overview

### List of goals stated in Proposal

What are the main points you wanted to research based on your proposal, will probably lead to the basic structure:

- ...

### Claims you can make with your analysis so far 
// Collect them first if you are not sure where to put them in the outline and highlight the key claims

- There is a strong relationship between x and y
- **We found x drugs and were able to validate dose dependency for n**
- Dataset y separates best into n clusters using  .. -> corresponds well with biology / is independent from the information we have from another data source

### Checklist

Things you should accomplish in the course and demonstrate with the report:

- [ ] descriptive statistics of core properties of your dataset(s) or derived data
- [ ] descriptive visualization to help with understanding the pecularities of your dataset
- [ ] Dimension reduction analysis OR useful clustering 
    - [ ] Visualize if informative
- [ ] statistical tests to substantiate core claims
    - [ ] Show that you investigated the preconditions/assumptions and made an informed choice for a particular test
- [ ] (linear) regression analysis of an important potential relationship in your datasets
    - [ ] *optional* how could this be used in a predictive context? can you validate the predictive power?

Additional criteria
- [ ] Describe criteria if you have to filter datasets, make selections.
    - [ ] If a decision is not based on a typical algorithm also describe how you came to an educated guess! Mention the literature you used or provide the plot/metric that let you make a more subjective decision.
- [ ] If you perform non-trivial data cleanup / imputation make sure that you don't inadvertendly affect your results and describe the procedure briefly

# Draft

## Title:

## Introduction
// State the main research questions you want to answer!

### Description of the data used (both part of introduction and results)
// This includes your exploratory plots!

**Claim:** dataset contains both inactive and active drugs (answered by Plot)

---
#### Plot: 
##### Caption draft
Distribution of x highlights the bimodal nature of  ...
##### Description if not obvious from the title:
Some nice histogram of x
##### Data prerequisites:
(if you still need to aggregate the data for that describe it)
... 

---

**Claim/Statement:** We have primarily lymphoma celllines and both acute and chronic to compare (table and references to literature)

---
#### Table: 
##### Caption draft
##### Description:
Crosstabulation of how many samples are present in certain categories
##### Data prerequisites:
(if you still need to aggregate the data for that describe it) 
group by something something

---


### Results (accompanied with the methods description)

---
#### Tested hypothesis: 
something is bigger than foo
##### Checklist:
- [ ] What is your hypothesis you want to answer -> map to alternative/null hypothesis 
- [ ] Have you confirmed that you chose the correct test
    - [ ] Requirements regarding sample size/independence/pairing
    - [ ] Assumptions about distributions validated
- [ ] How many tests do you actually perform in parallel -> correction factor for multiple testing

##### Data prerequisites:
(if you still need to aggregate the data for that describe it) 

---

### Discussion
// Keep it brief, and try to mostly argue with the results you got from the data (not too much uninformed speculation). 

// Use it primarily to reconnect to knowledge and questions from the literature.

* Striking observation corroborated by multiple results
* potentially confirmed by literature
* limitations of claims
* open questions

# Suggested placeholders until you have the plot/table/test description


---
#### Plot: 
##### Caption draft
Distribution of x highlights the bimodal nature of  ...
##### Description if not obvious from the title:
Some nice histogram of x factored by categories y
##### Data prerequisites:
(if you still need to aggregate the data for that describe it)
... 

---

---
#### Table: 
##### Caption draft
##### Description:
Crosstabulation of how many samples are present in certain categories
##### Data prerequisites:
(if you still need to aggregate the data for that describe it) 
group by something something

---

---
#### Tested hypothesis: 
something is bigger than foo
##### Checklist:
- [ ] What is your hypothesis you want to answer -> map to alternative/null hypothesis 
- [ ] Have you confirmed that you chose the correct test
    - [ ] Requirements regarding sample size/independence/pairing
    - [ ] Assumptions about distributions validated
- [ ] How many tests do you actually perform in parallel -> correction factor for multiple testing

##### Data prerequisites:
(if you still need to aggregate the data for that describe it) 

---