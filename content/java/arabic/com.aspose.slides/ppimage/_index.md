---
title: PPImage
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل صورةً في عرض تقديمي.
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

يمثل صورةً في عرض تقديمي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | إرجاع نسخة من بيانات الصورة. |
| [getImage()](#getImage--) | إرجاع نسخة من الصورة. |
| [getSvgImage()](#getSvgImage--) | إرجاع أو تعيين كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | إرجاع أو تعيين كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | يستبدل بيانات الصورة. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | يستبدل بيانات الصورة. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | يستبدل بيانات الصورة. |
| [getContentType()](#getContentType--) | إرجاع نوع MIME للصورة، مُرمَّزًا في BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | إرجاع عرض الصورة. |
| [getHeight()](#getHeight--) | إرجاع ارتفاع الصورة. |
| [getX()](#getX--) | إرجاع إزاحة X للصورة. |
| [getY()](#getY--) | إرجاع إزاحة Y للصورة. |
| [hashCode()](#hashCode--) | إرجاع رمز التجزئة للصورة. |
| [dispose()](#dispose--) | يحرر الكائن. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


إرجاع نسخة من بيانات الصورة. للقراءة فقط  byte[] .

**الإرجاع:**
byte[] - مصفوفة من البايتات
### getImage() {#getImage--}
```
public final IImage getImage()
```


إرجاع نسخة من الصورة. للقراءة فقط [IImage](../../com.aspose.slides/iimage).

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


إرجاع أو تعيين كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

تشير هذه القيمة إلى أن هذه الصورة تم إنشاؤها من SVG.

**الإرجاع:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


إرجاع أو تعيين كائن ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

تشير هذه القيمة إلى أن هذه الصورة تم إنشاؤها من SVG.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


يستبدل بيانات الصورة.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| newImageData | byte[] | بيانات الصورة الجديدة. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


يستبدل بيانات الصورة. انتباه: عندما تكون الصورة ملف ميتا - سيتم تحويلها إلى نقطية. استخدم ReplaceImage(byte[]) بدلاً من ذلك

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | الصورة الجديدة. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


يستبدل بيانات الصورة.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage الجديد. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


إرجاع نوع MIME للصورة، مُرمَّزًا في BinaryData (\#getBinaryData.getBinaryData). للقراءة فقط String.

**الإرجاع:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


إرجاع عرض الصورة. للقراءة فقط  int .

**الإرجاع:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


إرجاع ارتفاع الصورة. للقراءة فقط  int .

**الإرجاع:**
int
### getX() {#getX--}
```
public final int getX()
```


إرجاع إزاحة X للصورة. للقراءة فقط  int .

**الإرجاع:**
int
### getY() {#getY--}
```
public final int getY()
```


إرجاع إزاحة Y للصورة. للقراءة فقط  int .

**الإرجاع:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


إرجاع رمز التجزئة للصورة.

**الإرجاع:**
int - رمز التجزئة.
### dispose() {#dispose--}
```
public final void dispose()
```


يحرر الكائن.