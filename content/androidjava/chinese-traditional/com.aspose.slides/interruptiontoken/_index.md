---
title: InterruptionToken
second_title: Aspose.Slides for Android via Java API 參考文件
description: 此類別表示用於向長時間執行的任務發送中斷請求的標記。
type: docs
url: /zh-hant/com.aspose.slides/interruptiontoken/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

此類別表示用於向長時間執行的任務發送中斷請求的標記。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNone()](#getNone--) | 表示一個空的中斷標記。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果已請求中斷，則回傳 true。 |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 如果已請求中斷，則拋出例外。 |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

表示一個空的中斷標記。

--------------------

使用此標記時，長時間執行的作業將不會透過 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) 被中斷。

**回傳值:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

如果已請求中斷，則回傳 true。

**回傳值:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

如果已請求中斷，則拋出例外。