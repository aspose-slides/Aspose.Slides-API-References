---
title: TrendlineCollection
second_title: Aspose.Slides لـ Android عبر مرجع Java API
description: يمثل مجموعة من Trendline
type: docs
url: /ar/com.aspose.slides/trendlinecollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

يمثل مجموعة من Trendline
## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يجلب العنصر عند الفهرس المحدد. |
| [add(int trendlineType)](#add-int-) | يضيف Trendline الجديد في نهاية مجموعة ويعيده. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | يزيل القيمة المحددة. |
| [iterator()](#iterator--) | يعيد مُعددًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر Java للمجموعة بأكملها. |
| [getCount()](#getCount--) | يجلب عدد العناصر الموجودة فعليًا في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```


يجلب العنصر عند الفهرس المحدد. للقراءة فقط [Trendline](../../com.aspose.slides/trendline).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرتجعة:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```


يضيف Trendline الجديد في نهاية مجموعة ويعيده.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| trendlineType | int |  |

**القيمة المرتجعة:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```


يزيل القيمة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```


يعيد مُعددًا يتنقل عبر المجموعة.

**القيمة المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```


يعيد مكرّر Java للمجموعة بأكملها.

**القيمة المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```


يجلب عدد العناصر الموجودة فعليًا في المجموعة. للقراءة فقط int.

**القيمة المرتجعة:**
int