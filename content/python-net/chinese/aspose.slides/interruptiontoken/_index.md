---
title: InterruptionToken class
second_title: Aspose.Slides for Python 通过 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/interruptiontoken/
---
## InterruptionToken 类

此类表示用于向长时间运行的任务发信号，指示是否已请求中断的标记。

InterruptionToken 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`none`](/slides/python-net/zh/aspose.slides/interruptiontoken/none/) | 表示一个空的中断令牌。<br/>            使用此令牌时，长时间运行的操作永远不会通过 [`InterruptionTokenSource.interrupt`](/slides/python-net/zh/aspose.slides/interruptiontokensource/interrupt) 被中断。 |
| [`is_interruption_requested`](/slides/python-net/zh/aspose.slides/interruptiontoken/is_interruption_requested/) | 如果已请求中断，则返回 **bool**.true。 |

## 方法

| Method | Description |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/zh/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | 如果请求了中断，则抛出 OperationCanceledException。<br/>            |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)