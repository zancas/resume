Empirical Pythonista Seeking to Create Disruptive Technologies

(SDN, Distributed Computation, Cryptocurrencies, Distributed Storage, Privacy)

***********************

Contact Me, Josh Wilcox:
------------------------

Email:  wilcoxjg@gmail.com

Cell:   303-917-4176

Latest Version of This Resume: https://github.com/zancas/resume/blob/master/za_resume.rst

************************

Skills:
-------

Experienced:
~~~~~~~~~~~~

* software engineering: Python, test-driven development, git, Unix security
  and privacy tools, Tahoe-LAFS, bash
* biology: genetics, evolution

Proficient:
~~~~~~~~~~~

* JavaScript, C, crypto primitive applications (Diffie-Helman, signing, encrypting, etc.)

* probability, statistics, modeling, asymptotic algorithm analysis big-and-little-O


Professional Experience:
------------------------

Least Authority (2011-2014):
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Software Engineer, Operator, Customer Support

Developed features in support of the Simple Secure Storage Service (S4):
''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''

* Independently designed, implemented, and tested integration with Stripe
  payment processing system. (Twisted Web Python, JavaScript)
* Integrated S4 nodes into the Statmover monitoring service. (Python, bash,
  AWS EC2/S3)
* Automated PGP signup flow (Python, bash, Unittest, GPG)
* Automated service provisioning including: payment processing, EC2 launch
  and Tahoe provisioning. (Twisted Python, git, tahoe-LAFS)
* Identified inadequacy of previous system for snapshooted deployments,
  designed and implemented Git based snapshotted provisioning. (git)

Operated EC2 clusters
'''''''''''''''''''''

* Designed implemented and deployed customer EC2s (AWS EC2, Python, apt)
* Instrumented customer nodes to support foolscap gatherer and Statmover
  monitoring; configured and deployed foolscap gatherer monitors. (Python,
  foolscap, statmover, nagios)
* Maintained, extended and deployed Python Twisted webserver and Foolscap
  application server. (Twisted Python, foolscap)
* Testing (twisted.trial.unittest, mock, etc.)

  - website
  - service provisioning
  - email

Provided technical support to customers:
''''''''''''''''''''''''''''''''''''''''

* Responsible for responding to and resolving all customer requests in a timely manner using the zendesk issue tracking system

University of California Santa Cruz (2007-2011):
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Researcher, Teacher's Assistant: Genetics, Bioinformatics, Statistics

Bioinformatics:
'''''''''''''''

* Wrote python scripts to align molecular sequences and infer phylogenies from them.
* Used support vector  machines to detect open reading frames in large yeast data sets


Molecular Biology:
''''''''''''''''''

* Molecular cloning to identify molecular signals controlling neural
  development.
* Used custom java applications to analyze retinal neuron firing patterns and infer properties of mammalian visual processing.

Institute for Behavioral Genetics (2005-2007):
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* Used various statistical/clustering techniques eg MCMC and HMMs to detect
  confounding factors in large scale genetic association studies of
  molecular neural markers of addiction.

* Managed all types of lab data

* Wrote Python scripts automating data generation and analysis

University of Colorado (CU) Boulder, Undergraduate Research Grants:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Molecular Cellular and Developmental Biology (2002-2005):
'''''''''''''''''''''''''''''''''''''''''''''''''''''''''
* Wrote custom Python scripts to identify distinct clusters of microbial
  communities in the environment, resulting in peer reviewed publication
  (http://aem.asm.org/content/72/5/3685.full)
  and honors graduation.

Environmental Population and Organismic Biology (2000-2002):
''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''

* Performed electro-physiological experiments on zebrafish to determine how
  signal integration led to left-right decisions in various stimulus regimes

Sergeant, United State Marine Corps (USMC) (1995-1999):
'''''''''''''''''''''''''''''''''''''''''''''''''''''''

* performed duties of Infantryman, Honor Guard, Intelligence Analyst and Squad Leader


Education:
----------
* Fruita Monument Highschool (1995)
* University of Colorado, Boulder (1999-2005)

  - B.A. Molecular Biology, Magna Cum Laude, (GPA: 3.95)
  - B.A. Biochemistry
  - Minors- Applied Math(statistics), Chemistry
  - Certificates: Neuroscience
  - Emphasis: Computer Science

* University of California Santa Cruz (2007-2011)

  - Molecular Biology; Bioinformatics; Statistics (Nominated TA of the Year 2010)


* Miguel De Cervantes Spanish School, Xela, Guatemala (2011)


URLs to Interesting Bits of Code I've Written:
----------------------------------------------

For Leastauthority.com:
~~~~~~~~~~~~~~~~~~~~~~~

* `Storage Server (EC2) Deployments`_ (twisted)
* `Jasmine/JS Testing`_ and `Interface to Stripe Payment System`_ (jasmine,
  jquery, JS)
* `handling of Stripe, browser, and server interractions`_ (twisted.web)

For Tahoe-LAFS:
~~~~~~~~~~~~~~~

* `update and refactor metadata handling`_ and `tests of metadata handling`_
  (DRYness, unittest, mock)


.. _Storage Server (EC2) Deployments: https://github.com/zancas/leastauthority.com/blob/master/lae_automation/signup.py#L110
.. _Jasmine/JS Testing: https://github.com/zancas/leastauthority.com/blob/master/content/static/js/test/unit/unittests.js
.. _Interface to Stripe Payment System: https://github.com/zancas/leastauthority.com/blob/master/content/static/js/subscription_signup.js
.. _handling of Stripe, browser, and server interractions: https://github.com/zancas/leastauthority.com/blob/master/lae_site/handlers/submit_subscription.py
.. _update and refactor metadata handling: https://github.com/zancas/tahoe-lafs/blob/1634-dont-return-none_5/src/allmydata/web/common.py#L21
.. _tests of metadata handling: https://github.com/zancas/tahoe-lafs/blob/1634-dont-return-none_5/src/allmydata/test/test_json_metadata.py
