---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the source of .
type: docs
url: /zh/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

表示 [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) 的来源。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getToken()](#getToken--) | 返回绑定到此 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) 的新令牌。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果请求中断则返回 true，否则返回 false。 |
| [interrupt()](#interrupt--) | 初始化中断请求。 |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

返回绑定到此 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) 的新令牌。

**返回:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

如果请求中断则返回 true，否则返回 false。

**返回:**  
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

初始化中断请求。