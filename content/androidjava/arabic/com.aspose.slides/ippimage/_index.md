---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل صورة في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

يمثل صورة في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | يعيد نسخة من بيانات الصورة. |
| [getImage()](#getImage--) | يعيد نسخة من الصورة. |
| [getSvgImage()](#getSvgImage--) | يعيد أو يضبط كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | يعيد أو يضبط كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | يستبدل بيانات الصورة. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | يستبدل الصورة. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | يستبدل الصورة. |
| [getContentType()](#getContentType--) | يعيد نوع MIME للصورة، المشفر في \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | يعيد عرض الصورة. |
| [getHeight()](#getHeight--) | يعيد ارتفاع الصورة. |
| [getX()](#getX--) | يعيد إزاحة X للصورة. |
| [getY()](#getY--) | يعيد إزاحة Y للصورة. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

يعيد نسخة من بيانات الصورة. للقراءة فقط byte[].

**الإرجاع:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

يعيد نسخة من الصورة. للقراءة فقط \#getImage.getImage.

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

يعيد أو يضبط كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

تشير هذه القيمة إلى أن هذه الصورة تم إنشاؤها من SVG.

**الإرجاع:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

يعيد أو يضبط كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

تشير هذه القيمة إلى أن هذه الصورة تم إنشاؤها من SVG.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

يستبدل بيانات الصورة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| newImageData | byte[] | بيانات الصورة الجديدة. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

يستبدل الصورة. ملاحظة: عندما تكون الصورة ملف ميتافايل - سيتم تحويلها إلى نقطية. استخدم replaceImage(byte[]) بدلاً من ذلك

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | الصورة الجديدة. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

يستبدل الصورة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage الجديد. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

يعيد نوع MIME للصورة، المشفر في \#getBinaryData.getBinaryData. للقراءة فقط String.

**الإرجاع:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

يعيد عرض الصورة. للقراءة فقط int.

**الإرجاع:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

يعيد ارتفاع الصورة. للقراءة فقط int.

**الإرجاع:**
int
### getX() {#getX--}
```
public abstract int getX()
```

يعيد إزاحة X للصورة. للقراءة فقط int.

**الإرجاع:**
int
### getY() {#getY--}
```
public abstract int getY()
```

يعيد إزاحة Y للصورة. للقراءة فقط int.

**الإرجاع:**
int