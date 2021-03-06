![](assets/angel_logo.png)


[![license](http://img.shields.io/badge/license-BSD3-brightgreen.svg?style=flat)](https://github.com/tencent/angel/blob/master/LICENSE)
[![Release Version](https://img.shields.io/badge/release-1.0.0-red.svg)](https://github.com/tencent/angel/releases)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/tencent/angel/pulls)

**Angel** is a high-performance distributed machine learning platform based on the philosophy of Parameter Server. It is tuned for performance with big data from Tencent and has a wide range of applicability and stability, demonstrating increasing advantage in handling higher dimension model. Angel is jointly developed by Tencent and Peking University, taking account of both high availability  in industry and innovation in academia. 

With model-centered core design concept, **Angel** partitions parameters of complex models into multiple parameter-server nodes, and implements a variety of machine learning algorithms using efficient model-updating interfaces and functions, as well as flexible consistency model for synchronization.

**Angel** is developed with **Java** and **Scala**.  It supports running on **Yarn**. With **PS Service** abstraction, it supports **Spark on Angel**.  Graph computing and deep learning frameworks support is under development and with be released in the future. 

We welcome everyone interested in machine learning to contribute code, create issues or pull requests. Please refer to  [Angel Contribution Guide](https://github.com/Tencent/angel/blob/master/CONTRIBUTING.md) for more detail. 

## Introduction to Angel

* [Architecture](./docs/overview/architecture.md)
* [Code Framework](./docs/overview/framework.md)
* [Design](./docs/overview/design.md)
* [Spark on Angel](./docs/overview/spark_on_angel.md)


## Quick Start
* [Quick Start](./docs/tutorials/angel_ps_quick_start.md)
* [Spark on Angel Quick Start](./docs/tutorials/spark_on_angel_quick_start.md)


## Programming Guide

* [Angel Programming Guide](./docs/programmers_guide/angel_programing_guide.md)
* [Spark on Angel Programming Guide](./docs/programmers_guide/spark_on_angel_programing_guide.md)

## Design

* [Interface API](./docs/apis/interface_api.md)
* [psFunc](./docs/design/psfFunc.md)

## Algorithm

* [Logistic Regression](./docs/algo/lr_on_angel.md)
* [Matrix Factorization](./docs/algo/mf_on_angel.md)
* [SVM](./docs/algo/svm_on_angel.md)
* [KMeans](./docs/algo/kmeans_on_angel.md)
* [GBDT](./docs/algo/gbdt_on_angel.md)
* [LDA](./docs/algo/lda_on_angel.md)
* [LR (Spark on Angel)](./docs/algo/spark_on_angel_optimizer.md)

## Deployment

* [Source Code](./docs/deploy/source_compile.md)
* [Running on Local](./docs/deploy/local_run.md)
* [Running on Yarn](./docs/deploy/run_on_yarn.md)
* [Configuration Details](./docs/deploy/config_details.md)

## FAQ
* [Angel FAQ](https://github.com/Tencent/angel/wiki/Angel%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

## Papers
  1. Jiawei Jiang, Bin Cui, Ce Zhang, Lele Yu. [Heterogeneity-aware Distributed Parameter Servers](http://net.pku.edu.cn/~cuibin/Papers/2017%20sigmod.pdf). SIGMOD, 2017
  2. Jie Jiang, Lele Yu, Jiawei Jiang, Yuhong Liu and Bin Cui. [Angel: a new large-scale machine learning system](http://net.pku.edu.cn/~cuibin/Papers/2017NSRangel.pdf). National Science Review (NSR), 2017
  3. Jie Jiang, Jiawei Jiang,  Bin Cui and Ce Zhang. [TencentBoost: A Gradient Boosting Tree System with Parameter Server](http://net.pku.edu.cn/~cuibin/Papers/2017%20ICDE%20boost.pdf).	ICDE, 2017

