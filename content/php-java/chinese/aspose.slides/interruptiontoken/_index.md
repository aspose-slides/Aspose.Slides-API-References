---
title: InterruptionToken
second_title: Aspose.Sildes 用于 PHP 的 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/interruptiontoken/
---
## InterruptionToken 类

 此类表示用于向长期运行任务发出是否请求中断信号的令牌。

### getNone {#getNone}

| 名称 | 描述 |
| --- | --- |
| getNone () | 表示空的中断令牌。使用此令牌时，长期运行的操作永远不会通过 InterruptionTokenSource#interrupt 被中断。 |

 **返回:**
InterruptionToken


---


### isInterruptionRequested {#isInterruptionRequested}

| 名称 | 描述 |
| --- | --- |
| isInterruptionRequested () | 如果请求了中断，则返回 true。 |

 **返回:**
boolean


---


### throwIfInterruptionRequested {#throwIfInterruptionRequested}

| 名称 | 描述 |
| --- | --- |
| throwIfInterruptionRequested () | 如果请求了中断，则抛出异常。 |

 **返回:**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | OperationCanceledException | 当请求中断时抛出。 |


---