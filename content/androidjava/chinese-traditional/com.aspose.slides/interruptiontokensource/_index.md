---
title: InterruptionTokenSource
second_title: Aspose.Slides for Android via Java API 參考
description: 表示來源。
type: docs
url: /zh-hant/com.aspose.slides/interruptiontokensource/
---
**繼承：**
java.lang.Object
```
public class InterruptionTokenSource
```

表示 [InterruptionToken](../../com.aspose.slides/interruptiontoken) 的來源。

## 建構函式

| Constructor | Description |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | 建立一個新的 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)。 |

## 方法

| Method | Description |
| --- | --- |
| [getToken()](#getToken--) | 傳回與此 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) 綁定的新 token。 |
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

傳回與此 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) 綁定的新 token。

**傳回：**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)

### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

如果已請求中斷則傳回 true，否則傳回 false。

**傳回：**
boolean

### interrupt() {#interrupt--}
```
public final void interrupt()
```

初始化中斷請求。