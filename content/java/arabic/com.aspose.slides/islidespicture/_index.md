---
title: ISlidesPicture
second_title: مرجع API لـ Aspose.Slides للغة Java
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

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | إرجاع أو تعيين الصورة المضمنة. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | إرجاع أو تعيين الصورة المضمنة. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع أو تعيين عنوان URL للصورة المرتبطة. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع أو تعيين عنوان URL للصورة المرتبطة. |
| [getImageTransform()](#getImageTransform--) | إرجاع مجموعة تأثيرات تحويل الصورة. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

إرجاع أو تعيين الصورة المضمنة. قابل للقراءة/الكتابة [IPPImage](../../com.aspose.slides/ippimage).

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

إرجاع أو تعيين الصورة المضمنة. قابل للقراءة/الكتابة [IPPImage](../../com.aspose.slides/ippimage).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

إرجاع أو تعيين عنوان URL للصورة المرتبطة. قابل للقراءة/الكتابة String.

**القيمة المرجعة:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

إرجاع أو تعيين عنوان URL للصورة المرتبطة. قابل للقراءة/الكتابة String.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

إرجاع مجموعة تأثيرات تحويل الصورة. للقراءة فقط [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**القيمة المرجعة:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)