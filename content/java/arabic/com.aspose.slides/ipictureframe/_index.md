---
title: IPictureFrame
second_title: مرجع Aspose.Slides لواجهة برمجة التطبيقات لجافا
description: يمثل إطارًا يحتوي على صورة داخله.
type: docs
url: /ar/com.aspose.slides/ipictureframe/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

يمثِّل إطارًا يحتوي على صورة داخلية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | يرجع أقفال PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | يرجع كائن PictureFillFormat لإطار الصورة. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | يرجع أو يضبط مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | يرجع أو يضبط مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | يرجع أو يضبط مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | يرجع أو يضبط مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```


يرجع أقفال PictureFrame. للقراءة فقط [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**الإرجاع:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```


يرجع كائن PictureFillFormat لإطار الصورة. للقراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```


يرجع أو يضبط مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. عدد عائم للقراءة/الكتابة.

**الإرجاع:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```


يرجع أو يضبط مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. عدد عائم للقراءة/الكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```


يرجع أو يضبط مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. عدد عائم للقراءة/الكتابة.

**الإرجاع:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```


يرجع أو يضبط مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. عدد عائم للقراءة/الكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |