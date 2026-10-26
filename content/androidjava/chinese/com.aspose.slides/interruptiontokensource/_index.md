---
title: InterruptionTokenSource
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 … 的来源。
type: docs
url: /zh/com.aspose.slides/interruptiontokensource/
---
**继承：**
java.lang.Object
```
public class InterruptionTokenSource
```

表示 [InterruptionToken](../../com.aspose.slides/interruptiontoken) 的来源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | 创建一个新的 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getToken()](#getToken--) | 返回绑定到此 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) 的新令牌。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果请求中断则返回 true，否则返回 false。 |
| [interrupt()](#interrupt--) | 初始化中断请求。 |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```

创建一个新的 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)。

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```

返回绑定到此 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) 的新令牌。

**返回：**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

如果请求中断则返回 true，否则返回 false。

**返回：**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```

初始化中断请求。