---
title: IImage
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل صورة نقطية أو متجهة.
type: docs
url: /ar/com.aspose.slides/iimage/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

يمثل صورة نقطية أو متجهة.

--------------------

توفر هذه الواجهة تجريدًا عامًا لمعالجة كل من الصور النقطية والمتجهة. قد تختلف التنفيذات اعتمادًا على نوع الصورة الأساسي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Saves the image to a file. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Saves the image to a file in the specified format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves the image to a stream in the specified format. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Saves the image to a file in the specified format and quality. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Saves the image to a stream in the specified format and quality. |
| [getSize()](#getSize--) | Gets the size of the image. |
| [getWidth()](#getWidth--) | Gets the width of the image in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the image in pixels. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```


Saves the image to a file.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| filename | java.lang.String | المسار إلى الملف الذي سيتم حفظ الصورة فيه. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```


Saves the image to a file in the specified format.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| filename | java.lang.String | المسار إلى الملف الذي سيتم حفظ الصورة فيه. |
| format | int | تنسيق الصورة. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```


Saves the image to a stream in the specified format.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | التدفق الذي سيتم حفظ الصورة فيه. |
| format | int | تنسيق الصورة. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```


Saves the image to a file in the specified format and quality.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| filename | java.lang.String | المسار إلى الملف الذي سيتم حفظ الصورة فيه. |
| format | int | تنسيق الصورة. |
| quality | int | جودة الصورة المحفوظة (0 إلى 100). يؤثر هذا المعامل فقط على الحفظ في [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg)؛ بالنسبة لجميع الصيغ الأخرى، يتم تجاهله. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```


Saves the image to a stream in the specified format and quality.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | التدفق الذي سيتم حفظ الصورة فيه. |
| format | int | تنسيق الصورة. |
| quality | int | جودة الصورة المحفوظة (0 إلى 100). يؤثر هذا المعامل فقط على الحفظ في [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg)؛ بالنسبة لجميع الصيغ الأخرى، يتم تجاهله. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```


Gets the size of the image.

**القيمة المرجعة:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Gets the width of the image in pixels.

**القيمة المرجعة:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Gets the height of the image in pixels.

**القيمة المرجعة:**
int