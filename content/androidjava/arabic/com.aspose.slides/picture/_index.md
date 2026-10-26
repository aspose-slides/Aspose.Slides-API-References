---
title: Picture
second_title: Aspose.Slides للأندرويد عبر مرجع API جافا
description: يمثل صورة في عرض تقديمي.
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

يمثل صورة في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | يرجع أو يعيّن الصورة المدمجة. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | يرجع أو يعيّن الصورة المدمجة. |
| [getLinkPathLong()](#getLinkPathLong--) | يرجع أو يعيّن عنوان URL للصورة المرتبطة. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | يرجع أو يعيّن عنوان URL للصورة المرتبطة. |
| [getImageTransform()](#getImageTransform--) | يرجع مجموعة تأثيرات تحويل الصورة. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي. |
| [equals(Object obj)](#equals-java.lang.Object-) | يقارن مع الكائن المحدد. |
| [hashCode()](#hashCode--) | يرجع التجزئة. |
| [getSlide()](#getSlide--) | يرجع الشريحة الأصلية للصورة. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

يرجع الـ IPresentationComponent الأصل. للقراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getImage() {#getImage--}
```
public final IPPImage getImage()
```

يرجع أو يعيّن الصورة المدمجة. للقراءة/الكتابة [IPPImage](../../com.aspose.slides/ippimage).

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

يرجع أو يعيّن الصورة المدمجة. للقراءة/الكتابة [IPPImage](../../com.aspose.slides/ippimage).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

يرجع أو يعيّن عنوان URL للصورة المرتبطة. للقراءة/الكتابة String.

**الإرجاع:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

يرجع أو يعيّن عنوان URL للصورة المرتبطة. للقراءة/الكتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

يرجع مجموعة تأثيرات تحويل الصورة. للقراءة فقط [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**الإرجاع:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يقارن مع الكائن المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة. |

**الإرجاع:**
boolean - True إذا كان الكائنان متساويين، وإلا false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

يرجع التجزئة.

**الإرجاع:**
int - التجزئة.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأصلية للصورة. للقراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)