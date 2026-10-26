---
title: ISlidesPicture
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل صورةً في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/islidespicture/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

يمثل صورةً في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getImage()](#getImage--) | تُعيد أو تُضبط الصورة المضمَّنة. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | تُعيد أو تُضبط الصورة المضمَّنة. |
| [getLinkPathLong()](#getLinkPathLong--) | تُعيد أو تُضبط عنوان URL للصورة المرتبطة. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | تُعيد أو تُضبط عنوان URL للصورة المرتبطة. |
| [getImageTransform()](#getImageTransform--) | تُعيد مجموعة تأثيرات تحويل الصورة. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


تُعيد أو تُضبط الصورة المضمَّنة. قراءة/كتابة [IPPImage](../../com.aspose.slides/ippimage).

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


تُعيد أو تُضبط الصورة المضمَّنة. قراءة/كتابة [IPPImage](../../com.aspose.slides/ippimage).

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


تُعيد أو تُضبط عنوان URL للصورة المرتبطة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


تُعيد أو تُضبط عنوان URL للصورة المرتبطة. قراءة/كتابة String.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


تُعيد مجموعة تأثيرات تحويل الصورة. قراءة فقط [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**الإرجاع:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)