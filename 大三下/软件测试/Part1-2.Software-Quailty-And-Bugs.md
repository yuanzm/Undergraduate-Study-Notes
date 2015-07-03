# Software Quailty And Bugs

## 决定软件质量的因素
- Maintainability(可维护性)  
维护软件相对简单  
包括可变性，稳定性和可测试性
- Portability(可移植性)  
软件从一个系统迁移到另一个系统的能力
- Interoperability(互通性)  
一个系统与其他系统共同工作的能力
- Functionality(功能)  
以正确的方式给用户需要的，除此之外别无其他 
包括适用性，正确性，可靠性和安全性四个方面 
- Usability(可用性)  
最小化使用软件需要的气力(effort)  
包括可理解性，易学性，可操作性，Likeability(可爱性)
- Reliability(可靠性)  
包括可用性，容错性，可恢复性和Robustness(鲁棒性)4个方面

## 软件开发的铁三角
- Scope(Features,Functionality)
- Resource(Cost, Bugget)
- Schedule(Time)

## Failure, Fault and Error
- Failure: 可以观察到的系统不正确的行为或者状态
- Fault(Bug): 系统本身存在的缺陷引起的故障
- Error: 人为的操作引起的错误

## Bug的来源
- 客户端(Client): 不适当的软件复用
- 需求工程师: 遗漏，误解或故意偏差了软件需求
- 设计师：错误的算法，错误的边界条件处理，系统状态遗漏或缺失异常操作处理
- 程序员: 误解了需求文档, 精神状态不好的时候编码，不遵守文档和编码规范编码
- 质量保障团队(Quality assurance team): 未完成的测试计划，检测到的错误没有及时纠正，检测到的错误不完全纠正
- 操作员：操作错误
- 技术作家：遗漏了软件功能，没有及时更新软件错误的描述