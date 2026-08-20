---
title: IImage
second_title: مرجع API لـ Aspose.Slides للغة Java
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

توفر هذه الواجهة تجريدًا عامًا للتعامل مع كل من الصور النقطية والمتجهة. قد تختلف التنفيذات حسب نوع الصورة الأساسي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | يحفظ الصورة في ملف. |
| [save(String filename, int format)](#save-java.lang.String-int-) | يحفظ الصورة في ملف بالتنسيق المحدد. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | يحفظ الصورة في تدفق بالتنسيق المحدد. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | يحفظ الصورة في ملف بالتنسيق والجودة المحددين. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | يحفظ الصورة في تدفق بالتنسيق والجودة المحددين. |
| [getSize()](#getSize--) | يحصل على حجم الصورة. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة بالبكسل. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة بالبكسل. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

يحفظ الصورة في ملف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | java.lang.String | المسار إلى الملف حيث سيتم حفظ الصورة. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

يحفظ الصورة في ملف بالتنسيق المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | java.lang.String | المسار إلى الملف حيث سيتم حفظ الصورة. |
| format | int | تنسيق الصورة. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

يحفظ الصورة في تدفق بالتنسيق المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | التدفق حيث سيتم حفظ الصورة. |
| format | int | تنسيق الصورة. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

يحفظ الصورة في ملف بالتنسيق والجودة المحددين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | java.lang.String | المسار إلى الملف حيث سيتم حفظ الصورة. |
| format | int | تنسيق الصورة. |
| quality | int | جودة الصورة المحفوظة (0 إلى 100). هذا المعامل يؤثر فقط على الحفظ في [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg)؛ بالنسبة لجميع التنسيقات الأخرى، يتم تجاهله. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

يحفظ الصورة في تدفق بالتنسيق والجودة المحددين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | التدفق حيث سيتم حفظ الصورة. |
| format | int | تنسيق الصورة. |
| quality | int | جودة الصورة المحفوظة (0 إلى 100). هذا المعامل يؤثر فقط على الحفظ في [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg)؛ بالنسبة لجميع التنسيقات الأخرى، يتم تجاهله. |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

يحصل على حجم الصورة.

**الإرجاع:**
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

يحصل على عرض الصورة بالبكسل.

**الإرجاع:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

يحصل على ارتفاع الصورة بالبكسل.

**الإرجاع:**
int