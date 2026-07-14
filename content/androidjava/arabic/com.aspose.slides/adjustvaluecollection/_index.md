---
title: AdjustValueCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل مجموعة من تعديلات الأشكال.
type: docs
url: /ar/com.aspose.slides/adjustvaluecollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)  
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

يمثل مجموعة من تعديلات الشكل.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | إرجاع عدد من التعديلات. |
| [get_Item(int index)](#get-Item-int-) | إرجاع التعديل حسب الفهرس. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمعالجة المتعددة). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر المزامنة. |
| [iterator()](#iterator--) | إرجاع عداد للمجموعة بالكامل. |

### size() {#size--}
```
public final int size()
```

إرجاع عدد من التعديلات. int للقراءة فقط.

**الإرجاع:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

إرجاع التعديل حسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس التعديل. |

**الإرجاع:**  
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الأولي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمعالجة المتعددة). boolean للقراءة فقط.

**الإرجاع:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر المزامنة. Object للقراءة فقط.

**الإرجاع:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

إرجاع عداد للمجموعة بالكامل.

**الإرجاع:**  
com.aspose.ms.System.Collections.IEnumerator