---
title: GradientStopCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من نقاط التدرج اللوني.
type: docs
url: /ar/com.aspose.slides/gradientstopcollection/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

يمثل مجموعة من نقاط التدرج اللوني.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | يرجع عدد نقاط التدرج في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يرجع نقطة التدرج حسب الفهرس. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | ينشئ نقطة التدرج الجديدة ويُدرجها عند الفهرس المحدد في المجموعة. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | ينشئ نقطة التدرج الجديدة ويُدرجها عند الفهرس المحدد في المجموعة. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | ينشئ نقطة التدرج الجديدة ويُدرجها عند الفهرس المحدد في المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل نقطة التدرج عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع نقاط التدرج من المجموعة. |
| [iterator()](#iterator--) | يرجع كائن عداد (enumerator) يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مُكرِّر java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تُظهر ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر التزامن. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**القيمة المرجعة:**
long
### size() {#size--}
```
public final int size()
```

يرجع عدد نقاط التدرج في المجموعة. قراءة فقط int .

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

يرجع نقطة التدرج حسب الفهرس.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| color | java.awt.Color | لون نقطة التدرج الجديدة. |

**القيمة المرجعة:**
[IGradientStop](../../com.aspose.slides/igradientstop) - فهرس نقطة التدرج الجديدة في المجموعة.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| presetColor | int | لون نقطة التدرج الجديدة. |

**القيمة المرجعة:**
[IGradientStop](../../com.aspose.slides/igradientstop) - فهرس نقطة التدرج الجديدة في المجموعة.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| schemeColor | int | لون نقطة التدرج الجديدة. |

**القيمة المرجعة:**
[IGradientStop](../../com.aspose.slides/igradientstop) - فهرس نقطة التدرج الجديدة في المجموعة.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```

ينشئ نقطة التدرج الجديدة ويُدرجها عند الفهرس المحدد في المجموعة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدراج نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| color | java.awt.Color | لون نقطة التدرج الجديدة. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

ينشئ نقطة التدرج الجديدة ويُدرجها عند الفهرس المحدد في المجموعة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدراج نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| presetColor | int | لون نقطة التدرج الجديدة. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

ينشئ نقطة التدرج الجديدة ويُدرجها عند الفهرس المحدد في المجموعة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدراج نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| schemeColor | int | لون نقطة التدرج الجديدة. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل نقطة التدرج عند الفهرس المحدد.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس نقطة التدرج التي يجب حذفها. |
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع نقاط التدرج من المجموعة.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

يرجع كائن عداد (enumerator) يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - الـ IGenericEnumerator الذي يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

يرجع مُكرِّر java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Iterator من java.util للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تُظهر ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). قراءة فقط boolean .

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر التزامن. قراءة فقط Object.

**القيمة المرجعة:**
java.lang.Object