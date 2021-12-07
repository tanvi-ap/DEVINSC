# Detecting vulnerabilities in Source Code
Unrecognized flaws in software often can be the cause of attackers compromising a program and
forcing it to perform undesired behaviors including crashing or misusing user information.Thousands
of such vulnerabilities are reported each year to Common Vulnerabilities and Exposures Database.
(Total CVE records as of December 2021 are : 164960) These vulnerabilities are often caused due
to some subtle errors but they can propagate fast due to code reuse or software being open source.
The most famous example of such a vulnerability is the Equifax Breach which was termed as the most
economically damaging hack in the U.S. history. Hackers took advantage of a known vulnerability
in Apache struts Web application framework which is an open source project and this resulted in a
massive exposure of personal information of 143 million US citizens. 
Due to the volume of code being developed and the number of features available, developers
can no longer verify security flaws manually.Additionally not all developers are software security
experts. Traditional vulnerability detection tools rely on static or dynamic code analysis, symbolic
code execution or taint analysis.Custom manually generated templates or heuristics which have been
developed for a particular task are required for addressing specific vulnerability. Dynamic code
analysis techniques such as fuzzing trigger vulnerabilities to find them however they can only check
executed parts of the code. Fuzzing makes the analysis unmanageable since it exhaustively executes
every single path in the program. Detecting vulnerabilities is one of the tasks which is addressed
with new ML approaches. A property of such approaches is that they can work with numeric vectors
(feature vectors as inputs).Code embedding which is converting source code into such vectors can
be done either manually or using automation by applying ML based techniques. Adapting NLP
techniques such as text representation are popular. The accuracy of any prediction model relies on
the input provided empirical data is required for the SE task to be solved. Source control management
systems such as github are popular in development fields for source code management. Techniques
like static and dynamic analysis are used for finding vulnerabilities and are very popular. Machine
learning techniques help in shifting the focus from raw source code and mining information beyond
the code. With the amount of open source code available for analysis we can utilize this information
to train and prevent software vulnerabilities.


## References
https://towardsdatascience.com/introduction-to-git-data-extraction-and-analysis-in-python-e7e2bf9b4606

https://towardsdatascience.com/text-pre-processing-stop-words-removal-using-different-libraries-f20bac19929a

https://towardsdatascience.com/nlp-preprocessing-with-nltk-3c04ee00edc0

https://medium.com/swlh/how-to-train-word2vec-model-using-gensim-library-115b35440c90


