---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
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
| [getToken()](#getToken--) | يرجع الرمز الجديد المرتبط بهذا [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | يرجع true إذا تم طلب الانقطاع، false غير ذلك. |
| [interrupt()](#interrupt--) | تهيئة طلب الانقطاع. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


يرجع الرمز الجديد المرتبط بهذا [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**الإرجاع:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


يرجع true إذا تم طلب الانقطاع، false غير ذلك.

**الإرجاع:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


تهيئة طلب الانقطاع.