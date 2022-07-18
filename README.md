# 数据融合与数据智能导论

- [数据融合与数据智能导论](#数据融合与数据智能导论)
    - [前言](#前言)
    - [一、课程介绍](#一课程介绍)
    - [二、教学方法](#二教学方法)
    - [三、教学内容与要点](#三教学内容与要点)
      - [1. 数据对齐](#1-数据对齐)
      - [2.数据学习](#2数据学习)
      - [3.数据增强](#3数据增强)
      - [4.数据实时分析](#4数据实时分析)
      - [5.知识图谱](#5知识图谱)

### 前言

当前全球经济数字化转型不断加快，提升我国公民的数据素养具有重要意义。对于高校大学生乃至科研人员而言，数据素养或将成为重要的科学素养之一。本团队依据多年的研究成果，将数据融合和数据智能作为建立高校大学生数据素养的有效途径，培养学生自主地从数据中发现价值的能力。另外，本课程探索一种新型的“沉浸式代入教学模式”，通过制定自组织的课程内容、自主性的教学模式、自适应的评价体系，尝试解决学生日益增长的对社会技术加速变革中新生长知识的需求与传统课程体系所固定的知识内容之间的矛盾，以及学生日益丰富的获取信息的途径与传统相对单一的“灌输式”教学方式之间的矛盾。



### 一、课程介绍

在数字化转型时代，提高公民的数据素养（digital literacy）具有重要意义。2021年11月，中央网络安全和信息化委员会印发了《提升全民数字素养与技能行动纲要》，明确了提升全民数字素养与技能的指导思想、基本原则、发展目标等。数据素养强调处理、分析和解读数据的能力，对于高校大学生乃至科研人员而言，数据素养将成为与数学素养同等重要的科学素养之一。

本课程依据本团队多年的研究成果，将数据融合和数据智能作为建立数据素养的有效途径，围绕数据融合与数据智能的5个核心知识板块：数据对齐、数据学习、数据增强、实时分析和知识图谱，培养学生从数据中发现价值的能力。该5个模块与传统的数据管理具有显著的区别，传统的数据管理重点在于数据集成和数据分析，而上述5个模块则是从数据中发现价值的基本手段，是数据素养的基本内涵。



### 二、教学方法

在数字化转型时代，知识产生方式与获取方式都发生了改变，我们传承已久的人才培养模式面临着如下两点挑战：

**1）学生日益增长的对社会技术加速变革中新生长知识的需求与传统课程体系所固定的知识内容之间产生矛盾**。传统的课程体系将发展成熟的知识组织为相对固定的知识内容，转化的过程虽然严谨，但相对缓慢。而在数字化转型的时代，知识更迭的速度加快，传统的知识组织方式已难以满足当代学生对社会技术加速变革中新生长知识的需求。因此需要一种能够将知识迅速转化为课程内容的动态教学方式。

**2）学生日益丰富的获取信息的途径与传统相对单一的“灌输式”教学方式之间产生矛盾**。传统的教学方法为“灌输式”教学，极大地依赖于课堂讲授，由教师单方面输出，学生被动地接受。而在数字化转型的时代，学生获取知识与信息的途径随之多元化。互联网上充斥着众多的专业博客、学术讲座、开源代码等等，极大地扩展了学生自主学习的渠道，超越了传统课堂的时间与空间限制。



面对这样的发展趋势，为了尽快提升学生的数据素养，教师的教学的方法和形式也应与时俱进，探讨新的课程组织模式和教学模式，避免故步自封、照本宣科。**据此，我们做出初步尝试，提出一种沉浸式代入教学模式**，培养学生从数据中自主发现问题、解决问题、挖掘价值的能力。该方式具体包括以下三个特征：

**1）自组织的课程内容**。在本课程中，教师提供相对固定的主题内容，始终围绕数据融合与数据智能所涉及的5大知识板块，学习者可以依据主题自主选择阅读文献。这在一定程度上解决了学生对于前沿知识的需求。

**2）自主性的教学模式**。本课程通过具体的计算任务将学生代入到数据融合与数据智能的知识体系，促使学生自主地寻找资源，沉浸式地感受困难与挑战所在，激励学生在实践过程中形成独特的理解，从而培养学生自主解决问题的能力。

**3）自适应的评价体系**。考试为一种相对客观的考核方式，具有明确的标准，但学生自由发挥的空间小；实验、论文与报告等为一种相对主观的考核方式，学生可充分发挥主观能动性，但缺乏统一的量化标准。本课程采用二者相结合的方式：每一个计算任务都具有定量的评价指标，可以量化解决方案的有效性；同时通过报告等方式为学生提供自由发挥、交流讨论的空间，另外，通过学生提交实验结果的次数来量化学生的努力程度。自适应的评价体系可以根据更为真实全面地评判学生的学习效果。



具体地，针对每个任务，授课教师提供初步的解决方案（baseline）、参考书籍和相关文献；同学们通过阅读书籍和文献，思考如何将其应用于解决当前任务；助教组织学生们课堂汇报交流自己的经验与收获，从而达到互相分享经验的目标。另外，要求同学们动手编程实践，切实解决研究案例中的问题，提交实验结果，并实时展示实验效果排行榜，激励学生保质保量地完成案例任务。



**本课程所提出的基于计算任务的沉浸式代入教学与经典的案例教学有相似之处，同时也有显著区别**，具体表现在如下三点：

1）本课程使用计算任务引导学生进行实践与思考，计算任务与法律或商务案例具有本质区别；

2）本课程在开放式讨论的基础上，要求学生用代码切实完成任务要求；

3）本课程的代入式教学具有定量的评判标准：算法效果排行榜，可以有效地激励学生不断探索更为有效的解决方案。



**值得注意的是**，本课程具有一定的局限性：“沉浸式代入教学模式”并不通用，只适用于侧重实践、同时计算任务丰富的课程。其无法替代传统的经典课程，仅作为对于现有课程体系的有效补充与完善。



### 三、教学内容与要点

#### [1. 数据对齐]()

数据对齐旨在从不同结构，不同主题的数据库中识别与挖掘其中包含的“相同”实体对象，从而以此为依据进行更深入的挖掘研究。数据对齐数据对齐广泛存在于数据集成场景中：（1）剔除合并数据库的重复元组；(2)不同语料集中的实体匹配；(3)相似度挖掘。本课程中我们以中英文学者对齐这一计算任务为导向，引导学生进入课程，启发同学通过特征工程、机器学习等基本方法、来实现目标，提升对数据的分析理解能力，并最终能够探索利用数据对齐来解决数据融合中所面临的相关问题。

详情请见相应文件夹。

#### [2.数据学习]()

数据学习旨在从大量数据中学习并挖掘深层的语义与潜在价值，强调对数据的分析解读能力。不局限于传统的数据融合，数据学习的场景还包括：（1）方面观点挖掘；（2）细粒度情感分析；（3）语义表征等。本课程中我们设计了开放性计算任务，引导学生进入课程，启发同学通过经典机器学习基本方法、深度学习进阶方法认识任务、实现目标，并最终提升对数据的分析理解能力。

详情请见相应文件夹。

#### [3.数据增强](https://github.com/wamdmlab/Substituted_Learning/tree/main/%E6%95%B0%E6%8D%AE%E5%A2%9E%E5%BC%BA)

数据增强作为一种数据扩充技术，旨在让有限的数据产生更多的等价数据，是高质量数据融合与知识融合的基础之一。为了提升模型效果，众多研究者在模型改进中提出了诸多优秀方法，但较低质量的数据将限制模型效果，数据增强的重要性不言而喻。数据增强的应用场景主要包括：(1)数据样本较小，无法完成模型构建；（2）数据质量差，无法充分训练模型。据此，本课程中依托开放性研究场景，引导学生进入课程，启发学生如何通过合理地修正数据、扩充数据等方法，达到数据增强的目标，最终提升学生自主学习、研究能力。

详情请见相应文件夹。

#### [4.数据实时分析](https://github.com/wamdmlab/Substituted_Learning/tree/main/%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%97%B6%E5%88%86%E6%9E%90)

数据分析技术旨在从分析数据的过程和结果中获得有用的信息，用于让分析者产生认识和做出决策。数据分析按照时间特点可以分为实时数据分析和离线数据挖掘。在实时数据分析中，流数据的分析为其中一个大类。如在科学研究、智慧交通、无人驾驶、城市监控等领域，大规模分布式的传感器、监控摄像等装置的建设，产生了高速、海量的流数据。从流数据中进行实时分析，发现热点、稀有事件，依靠传统的人工+计算机搜索已无能为力。其中实时场景下的目标发现也成为了实时流数据处理中的重点和热点。近年来发展并盛行起来的数据智能技术正是从大数据中解决这一问题的利器。离线数据挖掘则是对大量累积的数据进行深入的数据分析，使用更复杂的技术，从数据中寻找更有价值的目标。

详情请见相应文件夹。

#### [5.知识图谱](https://github.com/wamdmlab/Substituted_Learning/tree/main/%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1)

知识图谱是组织知识的一种形式之一。通过知识图谱构建技术可以把非结构化数据转换成结构化形式从而有效管理、检索和利用非结构化数据。知识图谱被用于多个领域，且已有广泛研究。构建知识图谱主要由（1）实体识别；（2）关系抽取；两个部分组成。本课程中我们设计了开放性计算任务，引导学生进入课程，启发同学通过经典机器学习基本方法、深度学习进阶方法认识任务、实现目标，并最终理解基于知识图谱的数据组织能力。

详情请见相应文件夹。