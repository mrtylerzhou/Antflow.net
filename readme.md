﻿## 此项目为[antflow-activiti](https://gitee.com/tylerzhou/Antflow)的开源.net实现，同时也是纯血.net实现，没有任何java桥接技术，仅依赖了asp.net core,freesql,natasha等少数几个开源项目,已经私下开发了近半年了,核心功能已开发完成.已经调通的功能如下表，其它功能正在调试或者实现中。预计五一左右出第一个beta版。感兴趣的可以加入qq群进行沟通交流。

> 向一位.net界的不愿意透漏姓名大佬(同时也是我的老领导)致敬、向util作者何镇汐致谢、向freesql作者广州大佬致敬。没有他们支持、帮助、勉励甚至是督促，我没有毅力坚持这么长时间
>
> 向.net大佬谢杨老板致敬。他是一位学识渊博，犀利甚至略带刻薄的.net前辈。有了他的监督，我们如履薄冰，如临深渊，慌慌恐恐，战战兢兢不敢懈怠。
>
> 向所有关心关注本项目的用户致敬。你们的赞扬和肯定是我们前进的动力。你们的批评和吐槽是我们改进的方向。同时，不喜欢的绕道就行了，对于一些非善意的冷嘲热讽，挖苦嘲弄，我们也会反击！

+ 2025/03/22流程模板编辑已调通(目前.net版不支持并行审批,审批人规则只实现了指定人员)
+ 2025/03/23流程发起接口已调通
+ 2025/03/23流程同意接口已调通
+ 2025/03/23流程承办已调通
+ 2025/03/25 低代码表单已基本调通(还差curd了,基本链路都通了),从framework转到core还是不不少障碍,一些很简的知识花费了大量时间,不过还好都搞通了
+ 2025/03/28 一个问题卡了三天走不下去了,还好今天调通了.现在低代码流程/DIY流程(自定义表单流程)都调通了,流程完结后状态也ok.把所有缺失的建表语句都补上,用户可以初步测试一下流程了
+ 2025/03/31 周末增加了流程预览,流程审批路径查看.再加上待办,已办,传阅列表基本功能就完成啦!
