---
title: TextAnimation
second_title: Aspose.Slides لمرجع API جافا
description: تمثيل الرسوم المتحركة للنص.
type: docs
url: /ar/com.aspose.slides/textanimation/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

تمثيل الرسوم المتحركة للنص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | إضافة تأثير جديد إلى نهاية التسلسل الحالي إلى نهاية مجموعة الرسوم المتحركة للنص. |
| [getBuildType()](#getBuildType--) | قائمة نوع البناء (على سبيل المثال |
| [setBuildType(int value)](#setBuildType-int-) | قائمة نوع البناء (على سبيل المثال |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | تأثير الشكل المرتبط بالمجموعة أو لا (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | تأثير الشكل المرتبط بالمجموعة أو لا (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


إضافة تأثير جديد إلى نهاية التسلسل الحالي إلى نهاية مجموعة الرسوم المتحركة للنص. صالح فقط إذا كان عدد فقرات النص مساويًا أو أكبر من عدد تأثيرات هذه المجموعة!

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | الأنواع الفرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع المشغل للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**القيمة المرجعة:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


قائمة نوع البناء (على سبيل المثال الفقرة 1,2,3, جميعها مرة واحدة) للرسوم المتحركة للنص. قراءة/كتابة [BuildType](../../com.aspose.slides/buildtype).

**القيمة المرجعة:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


قائمة نوع البناء (على سبيل المثال الفقرة 1,2,3, جميعها مرة واحدة) للرسوم المتحركة للنص. قراءة/كتابة [BuildType](../../com.aspose.slides/buildtype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


تأثير الشكل المرتبط بالمجموعة أو لا (null). قراءة/كتابة [IEffect](../../com.aspose.slides/ieffect).

**القيمة المرجعة:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


تأثير الشكل المرتبط بالمجموعة أو لا (null). قراءة/كتابة [IEffect](../../com.aspose.slides/ieffect).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |