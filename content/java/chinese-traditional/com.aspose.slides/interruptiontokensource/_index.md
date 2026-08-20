---
title: InterruptionTokenSource
second_title: Aspose.Slides for Java API 參考文件
description: 表示來源。
type: docs
url: /zh-hant/com.aspose.slides/interruptiontokensource/
---
**繼承:**
java.lang.Object
```
public class InterruptionTokenSource
```

代表 [InterruptionToken](../../com.aspose.slides/interruptiontoken) 的來源。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | 建立一個新的 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getToken()](#getToken--) | 傳回繫結到此 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) 的新 token。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果已請求中斷則傳回 true，否則傳回 false。 |
| [interrupt()](#interrupt--) | 初始化中斷請求。 |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```

建立一個新的 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)。

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```

傳回繫結到此 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) 的新 token。

**返回:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

如果已請求中斷則傳回 true，否則傳回 false。

**返回:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```

初始化中斷請求。