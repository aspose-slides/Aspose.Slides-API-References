---
title: InterruptionToken
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: تمثل هذه الفئة الرمز المستخدم للإشارة إلى المهام طويلة التشغيل ما إذا تم طلب الإيقاف.
type: docs
url: /ar/com.aspose.slides/interruptiontoken/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

تمثل هذه الفئة الرمز المستخدم للإشارة إلى المهام طويلة التشغيل ما إذا تم طلب الإيقاف.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getNone()](#getNone--) | يمثل رمز إيقاف فارغ. |
| [isInterruptionRequested()](#isInterruptionRequested--) | إرجاع true إذا تم طلب الإيقاف. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | يرمى استثناءً إذا تم طلب الإيقاف. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

يمثل رمز إيقاف فارغ.

--------------------

لن يتم مقاطعة العمليات طويلة التشغيل عبر [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) عند استخدام هذا الرمز.

**الإرجاع:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

إرجاع true إذا تم طلب الإيقاف.

**الإرجاع:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

يرمي استثناءً إذا تم طلب الإيقاف.