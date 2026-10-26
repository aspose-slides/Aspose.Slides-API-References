---
title: IInterruptionTokenSource
second_title: Aspose.Slides 用於 Android 的 Java API 參考
description: 表示來源。
type: docs
url: /zh-hant/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

表示 [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) 的來源。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getToken()](#getToken--) | 返回綁定到此 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) 的新 token。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果已請求中斷則返回 true，否則返回 false。 |
| [interrupt()](#interrupt--) | 初始化中斷請求。 |

### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

返回綁定到此 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) 的新 token。

**返回:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

如果已請求中斷則返回 true，否則返回 false。

**返回:**  
boolean

### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

初始化中斷請求。