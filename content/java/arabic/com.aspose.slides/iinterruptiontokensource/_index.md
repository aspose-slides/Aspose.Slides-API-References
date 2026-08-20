---
title: IInterruptionTokenSource
second_title: مرجع API لـ Aspose.Slides for Java
description: يمثل مصدر .
type: docs
url: /ar/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

يمثل مصدر [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getToken()](#getToken--) | يرجع رمزًا جديدًا مرتبطًا بهذا [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | يرجع true إذا تم طلب المقاطعة، false وإلا. |
| [interrupt()](#interrupt--) | تهيئة طلب للمقاطعة. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


يرجع رمزًا جديدًا مرتبطًا بهذا [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**القيمة المرجعة:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


يرجع true إذا تم طلب المقاطعة، false وإلا.

**القيمة المرجعة:**  
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


تهيئة طلب للمقاطعة.