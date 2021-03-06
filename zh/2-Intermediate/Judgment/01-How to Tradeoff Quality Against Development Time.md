# 如何在开发质量与开发时间权衡
[//]: # (Version:1.0.0)
软件开发总是在工程该做什么与完成工程间妥协。但你可能被要求以牺牲你的工程适用性或商业适用性的方式，去交换工程的开发速度。例如，你可能被要求做一些糟糕的软件工程实践，但这将会导致大量维护问题。

如果这发生了，你的首要任务是通知你的团队，然后清楚地解释降低质量的代价。在这之后，你对这个问题的理解会比你的 boss 的理解还要更清晰。明白将会失去什么以及将要得到什么，以及在这次失去的东西，能在下一轮中得到什么。在这个过程中，由一个好工程提供的可见性应该会很有用。如果用质量换时间影响了质量保证工作，(向你的 boss 和质量保证人员)指出这个问题。如果用质量换时间会导致在之后的质量保证周期中出现更多的 bug，指出来。

如果她仍然坚持，你应该把劣质部分隔离到特殊的你可以在下一个开发周期计划重写或优化的组件中。向你的团队解释这个问题，这样他们可以为此做些计划。

忍者程序员在 Slashdot 写下了这样的格言：

> 记住，一个好的设计会被糟糕的代码实现弹回。如果好的接口和抽象在代码中到处存在，最后的重写会更加痛苦。如果写难以修复的清晰代码很困难，考虑是什么与核心设计冲突的东西导致了这个问题。

Next [如何管理软件依赖](02-How%20to%20Manage%20Software%20System%20Dependence.md)
