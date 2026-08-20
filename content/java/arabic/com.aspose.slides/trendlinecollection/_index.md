---
title: TrendlineCollection
second_title: Aspose.Slides لمرجع API لجافا
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

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [add(int trendlineType)](#add-int-) | يضيف Trendline جديد في نهاية المجموعة ويعيده. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | يزيل القيمة المحددة. |
| [iterator()](#iterator--) | يرجع مكرّرًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرّر java للمجموعة بالكامل. |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة فعلاً في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. قراءة فقط [Trendline](../../com.aspose.slides/trendline).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

يضيف Trendline جديد في نهاية المجموعة ويعيده.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| trendlineType | int |  |

**القيمة المرجعة:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

يزيل القيمة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

يرجع مكرّرًا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

يرجع مكرّر java للمجموعة بالكامل.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد العناصر الموجودة فعلاً في المجموعة. قراءة فقط int.

**القيمة المرجعة:**
int