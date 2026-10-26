---
title: InterruptionTokenSource
second_title: Aspose.Slides لـ Java API مرجع
description: يمثل مصدر .
type: docs
url: /ar/com.aspose.slides/interruptiontokensource/
---
**الوراثة:**
java.lang.Object
```
public class InterruptionTokenSource
```

يمثل مصدر [InterruptionToken](../../com.aspose.slides/interruptiontoken).
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | ينشئ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) جديدًا. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getToken()](#getToken--) | يعيد رمزًا جديدًا مرتبطًا بهذا [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | يعيد true إذا تم طلب الانقطاع، false غير ذلك. |
| [interrupt()](#interrupt--) | تهيئ طلب الانقطاع. |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```

ينشئ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) جديدًا.

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```

يعيد رمزًا جديدًا مرتبطًا بهذا [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**الإرجاع:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

يعيد true إذا تم طلب الانقطاع، false غير ذلك.

**الإرجاع:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```

تهيئ طلب الانقطاع.