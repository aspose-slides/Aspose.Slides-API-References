---
title: ITextAnimation
second_title: Aspose.Slides for Android عبر مرجع API للـ Java
description: يمثل تحريك النص.
type: docs
url: /ar/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

يمثل تحريك النص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Add new effect to the end of current sequence to end of group text animations. |
| [getBuildType()](#getBuildType--) | List of build type (for exp. |
| [setBuildType(int value)](#setBuildType-int-) | List of build type (for exp. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Linked shape effect with group or not (null) Read/write [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Linked shape effect with group or not (null) Read/write [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


أضف تأثيرًا جديدًا إلى نهاية التسلسل الحالي إلى نهاية مجموعة تحركات النص. يكون صالحًا فقط إذا كان عدد فقرات النص مساويًا أو أكبر من عدد تأثيرات هذه المجموعة!

**المعلمات:**
| المعامِل | النوع | الوصف |
| --- | --- | --- |
| effectType | int | نوع تأثير التحريك [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنواع فرعية لتأثير التحريك [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع الزناد للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**القيمة المرجعة:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


قائمة أنواع البناء (مثال: الفقرة 1،2،3، جميعًا مرة واحدة) لتحريك النص. قراءة/كتابة \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**القيمة المرجعة:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


قائمة أنواع البناء (مثال: الفقرة 1،2،3، جميعًا مرة واحدة) لتحريك النص. قراءة/كتابة \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**المعلمات:**
| المعامِل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


تأثير الشكل المرتبط بالمجموعة أو لا (null) قراءة/كتابة [IEffect](../../com.aspose.slides/ieffect).

**القيمة المرجعة:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


تأثير الشكل المرتبط بالمجموعة أو لا (null) قراءة/كتابة [IEffect](../../com.aspose.slides/ieffect).

**المعلمات:**
| المعامِل | النوع | الوصف |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |