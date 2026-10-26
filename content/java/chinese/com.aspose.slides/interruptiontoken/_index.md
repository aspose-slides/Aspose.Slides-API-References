---
title: InterruptionToken
second_title: Aspose.Slides 的 Java API 参考
description: 此类表示用于向长时间运行的任务发出是否请求中断信号的令牌。
type: docs
url: /zh/com.aspose.slides/interruptiontoken/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

此类表示用于向长时间运行的任务发出是否请求中断的信号的令牌。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getNone()](#getNone--) | 表示一个空的中断令牌。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果已请求中断，则返回 true。 |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 如果已请求中断，则抛出 an。 |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

表示一个空的中断令牌。

--------------------

使用此令牌时，长时间运行的操作将永远不会通过 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) 被中断。

**返回值：**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

如果已请求中断，则返回 true。

**返回值：**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

如果已请求中断，则抛出 an。