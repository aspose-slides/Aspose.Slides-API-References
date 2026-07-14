---
title: IImageCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
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
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | تعيد الصورة حسب فهرسها. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | إضافة صورة إلى عرض تقديمي. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | إضافة صورة إلى عرض تقديمي من تدفق. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | ينشئ ويضيف صورة إلى عرض تقديمي من تدفق. |
| [addImage(byte[] buffer)](#addImage-byte---) | يضيف صورة إلى عرض تقديمي من المخزن المؤقت المحدد. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | يضيف نسخة من صورة من عرض تقديمي آخر. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | إضافة صورة إلى عرض تقديمي من كائن SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

تُعيد الصورة حسب فهرسها.

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

إضافة صورة إلى عرض تقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | الصورة المراد إضافتها.

--------------------

يقوم هذا الأسلوب بتحويل ملفات WMF/EMF الوصفية إلى صورة PNG نقطية قبل إدراجها في عرض تقديمي. 

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - صورة مضافة.

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

إضافة صورة إلى عرض تقديمي من تدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق لإضافة الصورة منه.

--------------------

يمكن لهذا الأسلوب إضافة ملفات WMF/EMF الوصفية إلى عرض تقديمي دون تحويلها إلى صورة PNG نقطية. 

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - صورة مضافة.

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

ينشئ ويضيف صورة إلى عرض تقديمي من تدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق لإضافة ملف الصورة منه. |
| loadingStreamBehavior | int | السلوك الذي سيُطبق على التدفق. |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - تمت إضافة [IPPImage](../../com.aspose.slides/ippimage).

### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

يضيف صورة إلى عرض تقديمي من مخزن مؤقت محدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | byte[] | المخزن المؤقت. |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - صورة مضافة.

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
[IPPImage](../../com.aspose.slides/ippimage) - صورة مضافة.

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

إضافة صورة إلى عرض تقديمي من كائن SVG.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | كائن صورة SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - صورة مضافة.