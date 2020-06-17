# Active to Passive Voice

We present a two-stage approch to change sentences from active voice to passive voice.
In the first stage we extract the subject, object and verbs from the sentence if any. In the second stage we make changes to the extracted subject, object and verbs appropriately using case analysis. <br>
We handle some types of non-assertive sentences in the following way.
- Every sentence is converted to its assertive form by reordering. 
- The passive form output of the reordered sentence is reordered to suit the original input.

There is a pickle file - participles.pickle which contains list of irregular verbs.  
act_pas.py contains a function active_to_passive which takes a sentence as input and gives its passive voice as output.  
 
There are many more cases like - imperative sentences which haven't been handled.

IMPORTANT : Please install nltk before using the code.

I hope you like the code.
