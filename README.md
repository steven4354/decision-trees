# Decision Trees

**decision tree - a creation of "questions"**
**ID3 algo - the most common algo to generate a decision tree**

**random forests**

What if instead of making one decision tree you made several. As many as you wanted, really. A whole forest. Then each tree in the forest got a vote on the outcome for a given observation. Then you'd have a new model type: **Random Forest**. Random forests have become an incredibly popular technique for data scientists because it tends to be a top performer in a huge number of circumstances, with low variance and high accuracy.

params - tree (depth of tree, features used for splits) / forest (max number of trees)

**improvement**

Now, Random Forest models don't just create a ton of trees using the same data again and again and again. Instead they use bagging and random subspace to generate trees that are different. Without this, the trees could be incredibly similar (even identical), leading to correlation between trees and vulnerability to bias in the trees from some highly predictive features dominating every tree, creating a series of very similar trees with very similar, and potentially biased, predictions.

**bagging**. A subset of the observations is used to build a tree, it is placed back in

...



# TODOS:
- Explanation of Entropy https://courses.thinkful.com/data-201v1/assignment/3.2.1

- Explanation of ID3 algo https://courses.thinkful.com/data-201v1/assignment/3.2.2

- Explanation of bagging and random subspace https://courses.thinkful.com/data-201v1/assignment/3.2.3

- Sample of a random forests usage: https://courses.thinkful.com/data-201v1/project/3.2.5
