---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: كائن غير قابل للتغيير يحتوي على خصائص تعبئة الصورة.
type: docs
url: /ar/com.aspose.slides/ipicturefillformateffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

كائن غير قابل للتغيير يحتوي على خصائص تعبئة الصورة.

--------------------

هذه الواجهة تُستخدم كجزء من [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDpi()](#getDpi--) | يرجع الـ dpi المستخدم لتعبئة صورة. |
| [getPictureFillMode()](#getPictureFillMode--) | يرجع وضع تعبئة الصورة. |
| [getPicture()](#getPicture--) | يرجع الصورة. |
| [getCropLeft()](#getCropLeft--) | يرجع عدد النسب المئوية لعرض الصورة الحقيقي الذي يتم قصه من اليسار. |
| [getCropTop()](#getCropTop--) | يرجع عدد النسب المئوية لارتفاع الصورة الحقيقي الذي يتم قصه من الأعلى. |
| [getCropRight()](#getCropRight--) | يرجع عدد النسب المئوية لعرض الصورة الحقيقي الذي يتم قصه من اليمين. |
| [getCropBottom()](#getCropBottom--) | يرجع عدد النسب المئوية لارتفاع الصورة الحقيقي الذي يتم قصه من الأسفل. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

يرجع الـ dpi المستخدم لتعبئة صورة. للقراءة فقط int.

**الإرجاع:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

يرجع وضع تعبئة الصورة. للقراءة فقط [PictureFillMode](../../com.aspose.slides/picturefillmode).

**الإرجاع:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

يرجع الصورة. للقراءة فقط [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**الإرجاع:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

يرجع عدد النسب المئوية لعرض الصورة الحقيقي الذي يتم قصه من اليسار. للقراءة فقط float.

**الإرجاع:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

يرجع عدد النسب المئوية لارتفاع الصورة الحقيقي الذي يتم قصه من الأعلى. للقراءة فقط float.

**الإرجاع:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

يرجع عدد النسب المئوية لعرض الصورة الحقيقي الذي يتم قصه من اليمين. للقراءة فقط float.

**الإرجاع:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

يرجع عدد النسب المئوية لارتفاع الصورة الحقيقي الذي يتم قصه من الأسفل. للقراءة فقط float.

**الإرجاع:**
float