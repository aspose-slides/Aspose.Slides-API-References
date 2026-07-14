---
title: GradientStopCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل مجموعة من نقاط التدرج.
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

يمثل مجموعة من نقاط التدرج.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | يعيد عدد نقاط التدرج في مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد نقطة التدرج حسب الفهرس. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | ينشئ نقطة التدرج الجديدة ويُدرجها في الفهرس المحدد داخل المجموعة. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | ينشئ نقطة التدرج الجديدة ويُدرجها في الفهرس المحدد داخل المجموعة. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | ينشئ نقطة التدرج الجديدة ويُدرجها في الفهرس المحدد داخل المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل نقطة التدرج في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع نقاط التدرج من مجموعة. |
| [iterator()](#iterator--) | يعيد معدًّدا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر Java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long

### size() {#size--}
```
public final int size()
```

يعيد عدد نقاط التدرج في مجموعة. قراءة فقط int .

**الإرجاع:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

يعيد نقطة التدرج حسب الفهرس.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| color | java.lang.Integer | لون نقطة التدرج الجديدة. |

**الإرجاع:**
[IGradientStop](../../com.aspose.slides/igradientstop) - الفهرس الخاص بنقطة التدرج الجديدة في المجموعة.

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| presetColor | int | لون نقطة التدرج الجديدة. |

**الإرجاع:**
[IGradientStop](../../com.aspose.slides/igradientstop) - الفهرس الخاص بنقطة التدرج الجديدة في المجموعة.

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| schemeColor | int | لون نقطة التدرج الجديدة. |

**الإرجاع:**
[IGradientStop](../../com.aspose.slides/igradientstop) - الفهرس الخاص بنقطة التدرج الجديدة في المجموعة.

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

ينشئ نقطة التدرج الجديدة ويُدرجها في الفهرس المحدد داخل المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدراج نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| color | java.lang.Integer | لون نقطة التدرج الجديدة. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

ينشئ نقطة التدرج الجديدة ويُدرجها في الفهرس المحدد داخل المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدراج نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| presetColor | int | لون نقطة التدرج الجديدة. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

ينشئ نقطة التدرج الجديدة ويُدرجها في الفهرس المحدد داخل المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدراج نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| schemeColor | int | لون نقطة التدرج الجديدة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل نقطة التدرج في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس نقطة التدرج التي يجب حذفها. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع نقاط التدرج من مجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

يعيد معدًّدا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - مُعدِّد IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

يعيد مكرّر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - java.util.Iterator للمجموعة بأكملها.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). قراءة فقط boolean .

**الإرجاع:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. قراءة فقط Object.

**الإرجاع:**
java.lang.Object