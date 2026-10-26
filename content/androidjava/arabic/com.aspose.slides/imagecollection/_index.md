---
title: ImageCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل مجموعة من PPImage.
type: docs
url: /ar/com.aspose.slides/imagecollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

يمثل مجموعة من PPImage.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | إرجاع عدد من الصور في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | يضيف نسخة من صورة من عرض تقديمي آخر. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | إضافة صورة إلى عرض تقديمي. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | إضافة صورة إلى عرض تقديمي من تدفق. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | ينشئ ويضيف صورة إلى عرض تقديمي من تدفق. |
| [addImage(byte[] buffer)](#addImage-byte---) | يضيف صورة إلى عرض تقديمي من المخزن المؤقت المحدد. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | إضافة صورة إلى عرض تقديمي من كائن Svg. |
| [iterator()](#iterator--) | إرجاع عداد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع تكرار java للمجموعة بالكامل. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامن (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر التزامن. |
### size() {#size--}
```
public final int size()
```


إرجاع عدد من الصور في المجموعة. قراءة فقط  int .

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


يحصل على العنصر في الفهرس المحدد. قراءة فقط [IPPImage](../../com.aspose.slides/ippimage).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


يضيف نسخة من صورة من عرض تقديمي آخر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | الصورة المصدر. |

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


إضافة صورة إلى عرض تقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | الصورة لإضافتها.

--------------------

هذه الطريقة تحول ملفات WMF/EMF إلى صورة PNG نقطية قبل إدراجها في العرض التقديمي. |

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


إضافة صورة إلى عرض تقديمي من تدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | التدفق لإضافة الصورة منه.

--------------------

هذه الطريقة يمكنها إضافة ملفات WMF/EMF إلى عرض تقديمي دون تحويلها إلى صورة PNG نقطية. |

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


ينشئ ويضيف صورة إلى عرض تقديمي من تدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | التدفق لإضافة ملف الصورة منه. |
| loadingStreamBehavior | int | السلوك الذي سيتم تطبيقه على التدفق. |

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage) - المضافة [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


يضيف صورة إلى عرض تقديمي من المخزن المؤقت المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | byte[] | المخزن المؤقت. |

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


إضافة صورة إلى عرض تقديمي من كائن Svg.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | كائن صورة Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المضافة.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


إرجاع عداد يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


إرجاع تكرار java للمجموعة بالكامل.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامن (آمن للخيوط). قراءة فقط  boolean .

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


إرجاع جذر التزامن. قراءة فقط  Object .

**الإرجاع:**
java.lang.Object