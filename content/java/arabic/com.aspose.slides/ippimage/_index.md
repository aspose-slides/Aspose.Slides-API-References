---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: Represents an image in a presentation.
type: docs
url: /ar/com.aspose.slides/ippimage/
---
```
public interface IPPImage
```

يمثل صورةً في عرض تقديمي.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | إرجاع نسخة من بيانات الصورة. |
| [getImage()](#getImage--) | إرجاع نسخة من الصورة. |
| [getSvgImage()](#getSvgImage--) | إرجاع أو تعيين كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | إرجاع أو تعيين كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | يستبدل بيانات الصورة. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | يستبدل الصورة. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | يستبدل الصورة. |
| [getContentType()](#getContentType--) | إرجاع نوع MIME للصورة، مُشفَّر في \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | إرجاع عرض الصورة. |
| [getHeight()](#getHeight--) | إرجاع ارتفاع الصورة. |
| [getX()](#getX--) | إرجاع إزاحة X للصورة. |
| [getY()](#getY--) | إرجاع إزاحة Y للصورة. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

إرجاع نسخة من بيانات الصورة. للقراءة فقط byte[].

**الإرجاع:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

إرجاع نسخة من الصورة. للقراءة فقط \#getImage.getImage.

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

إرجاع أو تعيين كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

تشير هذه القيمة إلى أن هذه الصورة تم إنشاؤها من SVG.

**الإرجاع:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

إرجاع أو تعيين كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

تشير هذه القيمة إلى أن هذه الصورة تم إنشاؤها من SVG.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

يستبدل بيانات الصورة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| newImageData | byte[] | بيانات الصورة الجديدة. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

يستبدل الصورة. انتباه: عندما تكون الصورة ملف تعريف metafile - سيتم تحويلها إلى نقطية. استخدم replaceImage(byte[]) بدلاً من ذلك

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | الصورة الجديدة. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

يستبدل الصورة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage الجديد. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

إرجاع نوع MIME للصورة، مُشفَّر في \#getBinaryData.getBinaryData. للقراءة فقط String.

**الإرجاع:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

إرجاع عرض الصورة. للقراءة فقط int.

**الإرجاع:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

إرجاع ارتفاع الصورة. للقراءة فقط int.

**الإرجاع:**
int
### getX() {#getX--}
```
public abstract int getX()
```

إرجاع إزاحة X للصورة. للقراءة فقط int.

**الإرجاع:**
int
### getY() {#getY--}
```
public abstract int getY()
```

إرجاع إزاحة Y للصورة. للقراءة فقط int.

**الإرجاع:**
int