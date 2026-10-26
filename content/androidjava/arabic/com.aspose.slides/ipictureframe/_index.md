---
title: IPictureFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل إطارًا يحتوي على صورة بداخله.
type: docs
url: /ar/com.aspose.slides/ipictureframe/
---
**كل الواجهات المطبقة:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

يمثل إطارًا يحتوي على صورة بداخله.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | إرجاع أقفال PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | إرجاع كائن PictureFillFormat لإطار صورة. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | إرجاع أو ضبط مقياس الارتفاع (نسبي إلى حجم الصورة الأصلي) لإطار الصورة. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | إرجاع أو ضبط مقياس الارتفاع (نسبي إلى حجم الصورة الأصلي) لإطار الصورة. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | إرجاع أو ضبط مقياس العرض (نسبي إلى حجم الصورة الأصلي) لإطار الصورة. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | إرجاع أو ضبط مقياس العرض (نسبي إلى حجم الصورة الأصلي) لإطار الصورة. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```


إرجاع أقفال PictureFrame. للقراءة فقط [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**الإرجاع:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```


إرجاع كائن PictureFillFormat لإطار صورة. للقراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```


إرجاع أو ضبط مقياس الارتفاع (نسبي إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة float.

**الإرجاع:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```


إرجاع أو ضبط مقياس الارتفاع (نسبي إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```


إرجاع أو ضبط مقياس العرض (نسبي إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة float.

**الإرجاع:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```


إرجاع أو ضبط مقياس العرض (نسبي إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |