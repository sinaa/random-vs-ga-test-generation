### Random vs GA Study [(view page)](https://sinaa.github.io/random-vs-ga-test-generation/)
To support replication, this web page contains the experimental material used for the paper titled "**Random or Genetic Algorithm Search for Object-Oriented Test Suite Generation?**", accepted for publication at GECCO 2015. 

#### _Winner of the **Best Paper** award at GECCO2015, for the SBSE-SS track_


### GECCO 2015 Slides
[View / Download GECCO 2015 Slides](slides-gecco2015.pdf).

### Abstract
[View / Download PDF of the paper](shamshiri2015random.pdf).

> Achieving high structural coverage is an important aim in software testing. Several search-based techniques have proved successful at automatically generating tests that achieve high coverage. However, despite the well-established arguments behind using evolutionary search algorithms (e.g., genetic algorithms) in preference to random search, it remains an open question whether the benefits can actually be observed in practice when generating unit test suites for object-oriented classes. In this paper, we report an empirical study on the effects of using a genetic algorithm (GA) to generate test suites over generating test suites incrementally with random search, by applying the EvoSuite unit test suite generator to 1,000 classes randomly selected from the SF110 corpus of open source projects. Surprisingly, the results show little difference between the coverage achieved by test suites generated with evolutionary search compared to those generated using random search. A detailed analysis reveals that the genetic algorithm covers more branches of the type where standard fitness functions provide guidance. In practice, however, we observed that the vast majority of branches in the analyzed projects provide no such guidance.


### Artifacts
#### SF110 Repository
[SF110 Corpus of Classes](http://www.evosuite.org/experimental-data/sf110/)

#### 1000 Stratified Random Classes
[List of the 1000 classes taken from SF110](sf110_1000_classes.csv).

### EvoSuite Tool
EvoSuite along with the implementation of both GA and Random-Search algorithms used in this study are open source and [available on Github](https://github.com/EvoSuite/evosuite). For more information about EvoSuite and the documentation of the tool, please visit [evosuite.org](http://www.evosuite.org/).

### Bibtex Entry

    @inproceedings{shamshiri2015random,
      author    = "Shamshiri, Sina and Rojas, Jos\'{e} Miguel and Fraser, Gordon and McMinn, Phil",
      title     = "Random or Genetic Algorithm Search for Object-Oriented Test Suite Generation?",
      booktitle = "Genetic and Evolutionary Computation Conference (GECCO 2015)",
      pages     = "1367--1374",
      year      = "2015",
      publisher = "ACM"
    }

**Reference:** Sina Shamshiri, José Miguel Rojas, Gordon Fraser and Phil McMinn. Random or Genetic Algorithm Search for Object-Oriented Test Suite Generation? Genetic and Evolutionary Computation Conference (GECCO 2015), pp. 1367–1374, 2015.

**DOI:** [10.1145/2739480.2754696](http://dx.doi.org/10.1145/2739480.2754696)
