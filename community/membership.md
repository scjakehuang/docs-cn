# 社区成员

注意: 该文档依然可能会变化。

本文档将列出OpenTelemetry不同贡献者对应的职责。整个OpenTelemetry按照语言相关的SIGs(Special Interest
Group)被划分为多个子项目，因此这里的角色职责将限定在这些子项目下。


| **角色**   | **职责**                                  | **要求**                                             | **被谁定义**                                               |
| ---------- | ----------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| member(正式成员)     | 社区活跃贡献者，同时负责审查PR | 得到2个现有成员的支持，给项目做过多次贡献 | OpenTelemetry GitHub组织成员                             |
| approver(审批者)   | 对代码贡献进行审查、批准                       | 富有经验且活跃的代码Reviewer，同时也是一个子项目的贡献者| Github [CODEOWNER](https://help.github.com/en/articles/about-code-owners) |
| maintainer(维护者) | 管理子项目的整体方向和优先级        | 经过证明，富有责任心且在该子项目上极富经验 | [CODEOWNER](https://help.github.com/en/articles/about-code-owners), Github Team和代码仓库的所有权 |

## 新的贡献者

新的贡献者会得到现有社区成员的帮助：PR workflow，相关文档、交流频道指引等。


## 核心(Established)社区成员
核心的社区成员需要跟该文档中描述的原则贴近，熟悉整体项目的组织、角色、政策、过程、约定等，而且需要具备技术
写作能力。角色特定的责任和需求会在下面列举。

## 成员

成员是社区中持续活跃的贡献者，组织会分配issues和PR给他们，成员很有可能会参与到SIG中。

被以下定义: OpenTelemetry GitHub组织成员  

### 要求

- 在Github账户中开启 [two-factor 验证](https://help.github.com/articles/about-two-factor-authentication)
- 需要对项目或者社区做过多次贡献，贡献包括但是不限于:
  - 编写或者审查 PRs
  - 创建或者评论issues
  - 给SIGs、子项目、社区讨论作出贡献(例如：会议、聊天、邮件、讨论论坛等)
- [加入Gitter聊天频道](https://gitter.im/open-telemetry/community)
- 阅读过[贡献者准则](./CONTRIBUTING.md)
- 持续活跃的给一个或者更多的子项目做贡献
- 获得两个审核者/维护者的支持，以下是对支持者的要求:
  - 支持者必须跟候选人有紧密的交互 - 例如.代码/设计/提议的审查，issues上的协作等
  - 支持者必须是OpenTelemetry组织下任意仓库的审核者或者维护者
  - 支持者必须来自不同的公司，证明是通过社区发生的联系
- [创建申请issue](https://github.com/open-telemetry/community/issues/new?template=membership.md&title=REQUEST%3A%20New%20membership%20for%20%3Cyour-GH-handle%3E)
  - 在issue中通过`@mentioned`艾特你的支持者
  - 完成checklist上每一项要求([预览当前版本的模版](https://github.com/open-telemetry/community/blob/master/.github/ISSUE_TEMPLATE/membership.md))
  - 确保你填写的项目贡献能够代表你的工作(挑选最有价值的)
- 让你的支持者回复`+1`进行确认
- 一旦你的支持者确认，你的请求将被Steering Committe审核.  任何`SC`成员可以审核这些申请并且添加到组织中

### 责任 and 权利

- 对于被指派的issue和PR作出响应
- 对于贡献的代码必须要持续负责和维护，除非代码所有权发生了变更
  - 代码要有良好的测试
  - 测试要确保能够长期通过
  - 处理接受代码后发现的bug或提交的issue
- 成员可以通过Github workflow来做审查和批准，但是这不足以合并一个PR，无论如何都需要一个*审核者*来做审查
- 成员会被安排issues和PRs,而且人们可以要求成员来审查代码`/cc @username`

注意: 经常贡献代码的成员应该积极执行代码审查(Code Review)并努力成为该子项目的*审核者*

## 审核者

代码审核者可以审查和批准代码的提交，代码审查要聚焦在代码质量和正确性，批准聚焦在全盘可接受性：
前后/向前兼容性、是否符合API的约定、性能和正确性问题、跟其他系统的交互性等等。


被以下定义: [CODEOWNER
workflow](https://help.github.com/en/articles/about-code-owners).

审核者职责范围局限在代码库的某一个部分。

### 要求

以下的要求限定在审核者参与的代码部分中，这个在`CODEOWNER`有定义

- 代码审查持续3个月以上
- 为10个以上的重要PRs执行过代码审查
- 为30个以上的PRs执行过代码审查w和合并
- 被一个`维护者`提名
  - 其它维护者没有异议With no objections from other maintainers
  - 通过PR来更新`CODEOWNER`.

### 职责和权利

- 审核者身份是是否能接受大型代码贡献的前提条件
- 表现出良好的技术判断力
- 通过代码审查来保证项目的质量
  - 从整体角度来思考是否接受某个贡献，例如与其它功能的依赖关系，向前/向后兼容，API定义等
- 对于需要审查的请求积极响应
- 承担一定的贡献者导师角色
- 提供新成员加入的贡献证

## 维护者

注意: 这是比较高级、概括化的角色描述，对于维护者的具体职责描述必须在对应的SIG或者子项目中进行定义/

维护者是OpenTelemetry子项目的技术权威，他们必须拥有被证明过的良好判断力和责任心，以保证子项目的
良好运行。维护者要为子项目设定技术方向、证明设计的正确性等。



被以下定义: Github组织所有权、权限、 `CODEOWNERs`文件的条目

### 要求

在子项目的SIG中需要定义**如何成为该子项目的维护者**,不像之前定义的角色，一个子项目的owners会被限制在
一个相对小的范围内，然后随着子项目的要求而更新。

以下条款适用于想要成为子项目owner的人：

- 深刻理解子项目的技术目标和方向
- 深刻理解子项目的技术领域知识(特别是对应的语言)
- 通过以下行动持续的对设计和方向作出贡献:
  - 创建和审查提议
  - 初始化、贡献及解决讨论(邮件, GitHub issues,
    会议)
  - 识别PR设计和实现过程中的细微或复杂问题
- 通过实现或者审查对子项目直接作出贡献
- 与TSC定义的整个项目的目标、规范和设计原则保持一致，作为项目规范的一部分，引入一些通用的问题进行讨论

### 职责 and 权利

以下条款适用于想要成为子项目owner的人：

- 为子项目作出技术设计上的决定
- 为子项目设定技术方向和优先级
- 定义项目里程(milestones)和发布
- 作为整个子项目其它角色的导师角色
- 逐步增强 *审查者* and *维护者* 对workflow的关注 (例如：响应力,
  可用性等等)
- 确保子项目的持续健康:
  - 充分的单元测试覆盖率，保证发布的可靠性
  - 测试需要稳定可靠的通过(不脆弱)，当测试失败时，要及时修复
- 确保讨论和决策的过程是健康的
- 和其它维护者一起维护项目的整体健康