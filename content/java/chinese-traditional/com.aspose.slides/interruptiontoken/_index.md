---
title: InterruptionToken
second_title: Aspose.Slides for Java API 參考文件
description: 此類別代表用於為長時間執行的任務發送是否已請求中斷訊號的代幣。
type: docs
url: /zh-hant/com.aspose.slides/interruptiontoken/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

此類別代表用於向長時間執行的任務傳遞是否已請求中斷訊號的代幣。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getNone()](#getNone--) | 代表空的中斷代幣。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果已請求中斷，則返回 true。 |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 如果已請求中斷，則拋出例外。 |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

代表空的中斷代幣。

--------------------

使用此代幣時，長時間執行的作業將不會透過 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) 被中斷。

**傳回值：**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

如果已請求中斷，則返回 true。

**傳回值：**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

如果已請求中斷，則拋出例外。