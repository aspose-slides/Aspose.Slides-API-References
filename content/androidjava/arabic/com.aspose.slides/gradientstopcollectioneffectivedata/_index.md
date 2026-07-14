---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل مجموعة من كائنات GradientStopData.
type: docs
url: /ar/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)  
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

يمثل مجموعة من كائنات GradientStopData objects.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [size()](#size--) | يرجع عدد نقاط التدرج اللونية في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يرجع نقطة التدرج اللونية وفق الفهرس. |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مؤشراً من نوع java لكامل المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر المزامنة. |
### size() {#size--}
```
public final int size()
```

يرجع عدد نقاط التدرج اللونية في المجموعة. قراءة فقط int.

**الإرجاع:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

يرجع نقطة التدرج اللونية وفق الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

يرجع مؤشراً من نوع java لكامل المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف. |
| index | int | الفهرس الابتدائي في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). قراءة فقط boolean.

**الإرجاع:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر المزامنة. قراءة فقط Object.

**الإرجاع:**  
java.lang.Object