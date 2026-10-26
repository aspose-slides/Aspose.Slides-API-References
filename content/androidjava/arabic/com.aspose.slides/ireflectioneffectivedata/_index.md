---
title: IReflectionEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: كائن ثابت يمثل تأثير الانعكاس.
type: docs
url: /ar/com.aspose.slides/ireflectioneffectivedata/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

كائن ثابت يمثل تأثير الانعكاس.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | يحدد موقع البداية (على طول منحدر تدرج ألفا) لقيمة ألفا البداية (بالنسبة المئوية). |
| [getEndPosAlpha()](#getEndPosAlpha--) | يحدد موقع النهاية (على طول منحدر تدرج ألفا) لقيمة ألفا النهاية (بالنسبة المئوية). |
| [getFadeDirection()](#getFadeDirection--) | يحدد الاتجاه لإزاحة الانعكاس. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | تحديد شفافية الانعكاس الأولية. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | تحديد شفافية الانعكاس النهائية. |
| [getBlurRadius()](#getBlurRadius--) | نقطة الضبابية. |
| [getDirection()](#getDirection--) | اتجاه الانعكاس. |
| [getDistance()](#getDistance--) | مسافة الانعكاس. |
| [getRectangleAlign()](#getRectangleAlign--) | محاذاة المستطيل. |
| [getSkewHorizontal()](#getSkewHorizontal--) | يحدد زاوية الإمالة الأفقية. |
| [getSkewVertical()](#getSkewVertical--) | يحدد زاوية الإمالة العمودية. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. |
| [getScaleHorizontal()](#getScaleHorizontal--) | يحدد عامل القياس الأفقي، القياس السالب يسبب انعكاسًا. |
| [getScaleVertical()](#getScaleVertical--) | يحدد عامل القياس العمودي، القياس السالب يسبب انعكاسًا. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

يحدد موقع البداية (على طول منحدر تدرج ألفا) لقيمة ألفا البداية (بالنسبة المئوية). للق��اة فقط float.

**الإرجاع:**
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

يحدد موقع النهاية (على طول منحدر تدرج ألفا) لقيمة ألفا النهاية (بالنسبة المئوية). للق��اة فقط float.

**الإرجاع:**
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

يحدد الاتجاه لإزاحة الانعكاس. (الزاوية). للقرا��ة فقط float.

**الإرجاع:**
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

تحديد شفافية الانعكاس الأولية. (بالنسبة المئوية). للقرا��ة فقط float.

**الإرجاع:**
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

تحديد شفافية الانعكاس النهائية. (بالنسبة المئوية). للقرا��ة فقط float.

**الإرجاع:**
float
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

نقطة الضبابية. للقرا��ة فقط double.

**الإرجاع:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

اتجاه الانعكاس. للقرا��ة فقط float.

**الإرجاع:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

مسافة الانعكاس. للقرا��ة فقط double.

**الإرجاع:**
double
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

محاذاة المستطيل. للقرا��ة فقط [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**الإرجاع:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

يحدد زاوية الإمالة الأفقية. للقرا��ة فقط double.

**الإرجاع:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

يحدد زاوية الإمالة العمودية. للقرا��ة فقط double.

**الإرجاع:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. للقرا��ة فقط boolean.

**الإرجاع:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

يحدد عامل القياس الأفقي، القياس السالب يسبب انعكاسًا. (بالنسبة المئوية) للقرا��ة فقط double.

**الإرجاع:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

يحدد عامل القياس العمودي، القياس السالب يسبب انعكاسًا. (بالنسبة المئوية) للقرا��ة فقط double.

**الإرجاع:**
double