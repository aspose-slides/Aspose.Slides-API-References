---
title: IPictureFillFormatEffectiveData
second_title: مرجع API Aspose.Slides للغة جافا
description: كائن ثابت يحتوي على خصائص تعبئة الصورة.
type: docs
url: /ar/com.aspose.slides/ipicturefillformateffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

كائن ثابت يحتوي على خصائص تعبئة الصورة.

--------------------

هذه الواجهة تُستخدم كجزء من [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDpi()](#getDpi--) | يعيد الـ dpi الذي يُستخدم لتعبئة صورة. |
| [getPictureFillMode()](#getPictureFillMode--) | يعيد وضع تعبئة الصورة. |
| [getPicture()](#getPicture--) | يعيد الصورة. |
| [getCropLeft()](#getCropLeft--) | يعيد نسبة مئوية من عرض الصورة الحقيقي التي يتم قطعها من اليسار. |
| [getCropTop()](#getCropTop--) | يعيد نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قطعها من الأعلى. |
| [getCropRight()](#getCropRight--) | يعيد نسبة مئوية من عرض الصورة الحقيقي التي يتم قطعها من اليمين. |
| [getCropBottom()](#getCropBottom--) | يعيد نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قطعها من الأسفل. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

يعيد الـ dpi الذي يُستخدم لتعبئة صورة. قراءة فقط int.

**يعيد:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

يعيد وضع تعبئة الصورة. قراءة فقط [PictureFillMode](../../com.aspose.slides/picturefillmode).

**يعيد:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

يعيد الصورة. قراءة فقط [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**يعيد:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

يعيد نسبة مئوية من عرض الصورة الحقيقي التي يتم قطعها من اليسار. قراءة فقط float.

**يعيد:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

يعيد نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قطعها من الأعلى. قراءة فقط float.

**يعيد:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

يعيد نسبة مئوية من عرض الصورة الحقيقي التي يتم قطعها من اليمين. قراءة فقط float.

**يعيد:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

يعيد نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قطعها من الأسفل. قراءة فقط float.

**يعيد:**
float