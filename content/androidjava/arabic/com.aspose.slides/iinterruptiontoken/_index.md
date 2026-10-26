---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /ar/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

تمثل هذه الفئة الرمز المميز الذي يُستخدم للإشارة إلى المهام طويلة التشغيل ما إذا تم طلب المقاطعة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | إرجاع true إذا تم طلب المقاطعة. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | يرمي استثناءً إذا تم طلب المقاطعة. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

إرجاع true إذا تم طلب المقاطعة.

**الإرجاع:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

يرمي استثناءً إذا تم طلب المقاطعة.