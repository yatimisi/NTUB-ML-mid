# NTUB Machine Learning
> Report For Midterm Exam

## Research Topic

Use four of the five personality traits to infer whether you are a cheerful person.

## Reserach Method

### Environment

* Python Version: `3.6.8`
* Packages:
  * pandas==1.0.3
  * matplotlib==3.2.1
  * jupyter==1.0.0
  * numpy==1.18.2
  * tensorflow-datasets==3.0.0
  * tensorflow-hub==0.8.0
  * tensorflow-addons==0.9.1
  * tensorflow==2.0.0
  * seaborn==0.10.0
  * scipy==1.4.1

### Dataset

* [Big Five Personality Test
](https://www.kaggle.com/tunguz/big-five-personality-test)

### Steps
1. Handle Big Five Personality Data
2. Reverse value
3. Factor aggregation
4. Random Data
5. Normalization
6. Establish training data in Numpy array format
7. Create Model
    1. Initialising the ANN
    2. Adding the input layer and the first hidden layer
    3. Compiling the ANN
    4. Set callback function
    5. Fit
8. Verify the effectiveness
9. Results of training
    1. Percentage Error
    2. acc curve diagram
    3. loss curve diagram

## Research Conclusion

Success rate inferred: `89.94%`

## References

* https://www.kaggle.com/tunguz/big-five-personality-test
