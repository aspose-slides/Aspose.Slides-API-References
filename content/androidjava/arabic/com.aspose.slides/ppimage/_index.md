---
title: PPImage
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل صورة في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/ppimage/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable  
```
public class PPImage implements IPPImage, System.IDisposable
```

يمثل صورة في عرض تقديمي.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | إرجاع نسخة من بيانات الصورة. |
| [getImage()](#getImage--) | إرجاع نسخة من الصورة. |
| [getSvgImage()](#getSvgImage--) | إرجاع أو ضبط كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | إرجاع أو ضبط كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | يستبدل بيانات الصورة. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | يستبدل بيانات الصورة. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | يستبدل بيانات الصورة. |
| [getContentType()](#getContentType--) | إرجاع نوع MIME للصورة، المشفر في BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | إرجاع عرض الصورة. |
| [getHeight()](#getHeight--) | إرجاع ارتفاع الصورة. |
| [getX()](#getX--) | إرجاع إزاحة X للصورة. |
| [getY()](#getY--) | إرجاع إزاحة Y للصورة. |
| [hashCode()](#hashCode--) | إرجاع الرمز التجزيئي (hash code) للصورة. |
| [dispose()](#dispose--) | يقوم بتحرير الكائن. |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

إرجاع نسخة من بيانات الصورة. للقراة فقط  byte[] .

**الإرجاع:**  
byte[] - مجموعة من البايتات

### getImage() {#getImage--}
```
public final IImage getImage()
```

إرجاع نسخة من الصورة. للقراة فقط [IImage](../../com.aspose.slides/iimage).

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage)

### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

إرجاع أو ضبط كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

هذه القيمة تشير إلى أن هذه الصورة تم إنشاؤها من SVG.

**الإرجاع:**  
[ISvgImage](../../com.aspose.slides/isvgimage)

### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

إرجاع أو ضبط كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

هذه القيمة تشير إلى أن هذه الصورة تم إنشاؤها من SVG.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

يستبدل بيانات الصورة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| newImageData | byte[] | بيانات الصورة الجديدة. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

يستبدل بيانات الصورة. انتباه: عندما تكون Image ملف ميتافيل - سيتم تحويلها إلى نقطية. استخدم ReplaceImage(byte[]) بدلاً من ذلك

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | الصورة الجديدة. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

يستبدل بيانات الصورة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | الـ IPPImage الجديد. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

إرجاع نوع MIME للصورة، المشفر في BinaryData (\#getBinaryData.getBinaryData). للقراة فقط String.

**الإرجاع:**  
java.lang.String

### getWidth() {#getWidth--}
```
public final int getWidth()
```

إرجاع عرض الصورة. للقراة فقط  int .

**الإرجاع:**  
int

### getHeight() {#getHeight--}
```
public final int getHeight()
```

إرجاع ارتفاع الصورة. للقراة فقط  int .

**الإرجاع:**  
int

### getX() {#getX--}
```
public final int getX()
```

إرجاع إزاحة X للصورة. للقراة فقط  int .

**الإرجاع:**  
int

### getY() {#getY--}
```
public final int getY()
```

إرجاع إزاحة Y للصورة. للقراة فقط  int .

**الإرجاع:**  
int

### hashCode() {#hashCode--}
```
public int hashCode()
```

إرجاع الرمز التجزيئي للصورة.

**الإرجاع:**  
int - رمز تجزيئي.

### dispose() {#dispose--}
```
public final void dispose()
```

يقوم بتحرير الكائن.