I faced some challenges in task 3
- the model missed several entities, returned wrong, and even returned nothing, I tried many sentences and even the trained sentce still the same result nothing
- I reduced the dropout rate from 0.2 to 0.0 to address the problem
- change the annotation method into a list of entity–label pairs and in the for loop generated their character offsets using index() and len()
- set a random seed for reproducibility before training
- then tested on the task 3 sentence before the new sentence.
and entity recognition improved.
