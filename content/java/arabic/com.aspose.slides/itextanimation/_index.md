---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: تمثيل حركة النص.
type: docs
url: /ar/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

تمثيل حركة النص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | إضافة تأثير جديد إلى نهاية التسلسل الحالي إلى نهاية مجموعة رسومات النص. |
| [getBuildType()](#getBuildType--) | قائمة نوع البناء (مثلاً |
| [setBuildType(int value)](#setBuildType-int-) | قائمة نوع البناء (مثلاً |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | تأثير الشكل المرتبط مع مجموعة أو لا (null) قراءة/كتابة [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | تأثير الشكل المرتبط مع مجموعة أو لا (null) قراءة/كتابة [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

إضافة تأثير جديد إلى نهاية التسلسل الحالي إلى نهاية مجموعة رسومات النص. يكون صالحًا فقط إذا كان عدد فقرات النص مساويًا أو أكبر من عدد تأثيرات هذه المجموعة!

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنواع فرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع المشغل للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**القيمة المرتجعة:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

قائمة نوع البناء (على سبيل المثال الفقرة 1،2،3، جميعها مرة واحدة) لحركة النص. قراءة/كتابة \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**القيمة المرتجعة:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

قائمة نوع البناء (على سبيل المثال الفقرة 1،2،3، جميعها مرة واحدة) لحركة النص. قراءة/كتابة \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

تأثير الشكل المرتبط مع مجموعة أو لا (null) قراءة/كتابة [IEffect](../../com.aspose.slides/ieffect).

**القيمة المرتجعة:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

تأثير الشكل المرتبط مع مجموعة أو لا (null) قراءة/كتابة [IEffect](../../com.aspose.slides/ieffect).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |