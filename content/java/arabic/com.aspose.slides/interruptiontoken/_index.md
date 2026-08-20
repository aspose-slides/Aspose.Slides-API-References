---
title: InterruptionToken
second_title: مرجع API لـ Aspose.Slides للغة Java
description: هذه الفئة تمثل الرمز المستخدم للإشارة إلى المهام طويلة الأمد ما إذا تم طلب الإيقاف.
type: docs
url: /ar/com.aspose.slides/interruptiontoken/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

هذه الفئة تمثل الرمز المستخدم للإشارة إلى المهام طويلة الأمد ما إذا تم طلب الإيقاف.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNone()](#getNone--) | يمثل رمز مقاطعة فارغ. |
| [isInterruptionRequested()](#isInterruptionRequested--) | يرجع true إذا تم طلب الإيقاف. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | يرمي استثناءً إذا تم طلب الإيقاف. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

يمثل رمز مقاطعة فارغ.

--------------------

العمليات طويلة الأمد لن تُقاطع أبداً عبر [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) عند استخدام هذا الرمز.

**القيمة المرجعة:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

يرجع true إذا تم طلب الإيقاف.

**القيمة المرجعة:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

يرمي استثناءً إذا تم طلب الإيقاف.