---
title: IGradientFormatEffectiveData
second_title: مرجع API Aspose.Slides لجافا
description: كائن غير قابل للتغيير يحتوي على خصائص تعبئة التدرج الفعّالة.
type: docs
url: /ar/com.aspose.slides/igradientformateffectivedata/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

كائن غير قابل للتغيير يحتوي على خصائص تعبئة التدرّج الفعّالة.

--------------------

تُستخدم هذه الواجهة كجزء من [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) و [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## الطرق

| Method | Description |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | يعيد وضع الانعكاس لتدرّج اللون. |
| [getGradientDirection()](#getGradientDirection--) | يعيد نمط التدرّج. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | يعيد زاوية التدرّج. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | يحدد ما إذا كان التدرّج مُقاسًا. |
| [getGradientShape()](#getGradientShape--) | يعيد شكل التدرّج. |
| [getGradientStops()](#getGradientStops--) | يعيد مجموعة نقاط التدرّج. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

يعيد وضع الانعكاس لتدرّج اللون. القراءة فقط [TileFlip](../../com.aspose.slides/tileflip).

**القيمة المرجعة:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

يعيد نمط التدرّج. القراءة فقط [GradientDirection](../../com.aspose.slides/gradientdirection).

**القيمة المرجعة:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

يعيد زاوية التدرّج. القراءة فقط float.

**القيمة المرجعة:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

يقرر ما إذا كان التدرّج مُقاسًا. القراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

يعيد شكل التدرّج. القراءة فقط [GradientShape](../../com.aspose.slides/gradientshape).

**القيمة المرجعة:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

يعيد مجموعة نقاط التدرّج. القراءة فقط [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**القيمة المرجعة:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)