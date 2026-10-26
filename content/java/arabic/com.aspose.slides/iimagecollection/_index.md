---
title: IImageCollection
second_title: مرجع API لـ Aspose.Slides for Java
description: يمثل مجموعة من PPImage.
type: docs
url: /ar/com.aspose.slides/iimagecollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

يمثل مجموعة من PPImage.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد الصورة بحسب فهرسها. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | إضافة صورة إلى العرض التقديمي. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | إضافة صورة إلى العرض التقديمي من تدفق. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | ينشئ ويضيف صورة إلى العرض التقديمي من تدفق. |
| [addImage(byte[] buffer)](#addImage-byte---) | يضيف صورة إلى العرض التقديمي من المخزن المحدد. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | يضيف نسخة من صورة من عرض تقديمي آخر. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | إضافة صورة إلى العرض التقديمي من كائن SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

يعيد الصورة بحسب فهرسها.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس. |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - صورة.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

إضافة صورة إلى العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | الصورة التي يتم إضافتها. |

--------------------

تحول هذه الطريقة ملفات WMF/EMF إلى صورة PNG نقطية قبل إدراجها في العرض التقديمي. |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

إضافة صورة إلى العرض التقديمي من تدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | التدفق لإضافة الصورة منه. |

--------------------

تستطيع هذه الطريقة إضافة ملفات WMF/EMF إلى العرض التقديمي دون تحويلها إلى صورة PNG نقطية. |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

ينشئ ويضيف صورة إلى العرض التقديمي من تدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | التدفق لإضافة ملف الصورة منه. |
| loadingStreamBehavior | int | السلوك الذي سيُطبق على التدفق. |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - تمت إضافة [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

يضيف صورة إلى العرض التقديمي من المخزن المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | byte[] | المخزن. |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

يضيف نسخة من صورة من عرض تقديمي آخر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | صورة المصدر. |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

إضافة صورة إلى العرض التقديمي من كائن SVG.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | كائن صورة SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.