---
title: Picture
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل صورةً في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/picture/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)  
```
public final class Picture implements IPVIObject, ISlidesPicture
```

يمثل صورةً في عرض تقديمي.
## الأساليب

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | إرجاع أو تعيين الصورة المضمنة. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | إرجاع أو تعيين الصورة المضمنة. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع أو تعيين عنوان URL للصورة المرتبطة. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | إرجاع أو تعيين عنوان URL للصورة المرتبطة. |
| [getImageTransform()](#getImageTransform--) | إرجاع مجموعة تأثيرات تحويل الصورة. |
| [getPresentation()](#getPresentation--) | إرجاع العرض التقديمي. |
| [equals(Object obj)](#equals-java.lang.Object-) | مقارنة مع الكائن المحدد. |
| [hashCode()](#hashCode--) | إرجاع التجزئة. |
| [getSlide()](#getSlide--) | إرجاع الشريحة الأصلية للصورة. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**الإرجاع:**  
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

الإصدار. long للقراءة فقط.

**الإرجاع:**  
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

إرجاع IPresentationComponent الأصلية. [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent) للقراءة فقط.

**الإرجاع:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

إرجاع أو تعيين الصورة المضمنة. [IPPImage](../../com.aspose.slides/ippimage) قراءة/كتابة.

**الإرجاع:**  
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

إرجاع أو تعيين الصورة المضمنة. [IPPImage](../../com.aspose.slides/ippimage) قراءة/كتابة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

إرجاع أو تعيين عنوان URL للصورة المرتبطة. String قراءة/كتابة.

**الإرجاع:**  
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

إرجاع أو تعيين عنوان URL للصورة المرتبطة. String قراءة/كتابة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

إرجاع مجموعة تأثيرات تحويل الصورة. [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection) للقراءة فقط.

**الإرجاع:**  
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

إرجاع العرض التقديمي. [IPresentation](../../com.aspose.slides/ipresentation) للقراءة فقط.

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

مقارنة مع الكائن المحدد.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة. |

**الإرجاع:**  
boolean - صحيح إذا كانت الكائنات متساوية، وإلا خطأ.
### hashCode() {#hashCode--}
```
public int hashCode()
```

إرجاع التجزئة.

**الإرجاع:**  
int - تجزئة.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

إرجاع الشريحة الأصلية للصورة. [IBaseSlide](../../com.aspose.slides/ibaseslide) للقراءة فقط.

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)