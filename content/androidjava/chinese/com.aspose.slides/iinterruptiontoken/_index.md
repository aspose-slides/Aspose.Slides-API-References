---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: 此类表示用于向长时间运行的任务发出中断请求信号的令牌。
type: docs
url: /zh/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

此类表示用于向长时间运行的任务发出中断请求信号的令牌。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果请求了中断则返回 true。 |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 如果请求了中断则抛出异常。 |

### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

如果请求了中断则返回 true。

**返回：**
boolean

### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

如果请求了中断则抛出异常。