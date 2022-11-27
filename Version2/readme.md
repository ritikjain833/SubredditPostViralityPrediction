Steps to run the code:</br>
    1. Run all cells in addingNodes: Creates nodes for each author in the January data of specified subreddit.</br>
    2. Run all cells in addingEdges: Adds edges for each comment such that there is a directed edge A->B such that A has commented on a post of B. </br>
    3. Run all cells in creatingFeatureVector: Creates features vector for features like: pageRank, degreeCentrality, sentimentScore, numberOfComments and dateTimeOfPost.</br>
    4. Run all cells in randomForestClassifier: Creates a classification model to predict whether the post will be viral or not.</br>
    5. Run all cells in neural_network_model: Creates a neural network in Tensorflow Keras to predict the exact score that the post will achieve.
