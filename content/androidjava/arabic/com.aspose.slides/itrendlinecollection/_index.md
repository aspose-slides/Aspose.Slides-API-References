---
title: ITrendlineCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من TrendlineEx
type: docs
url: /ar/com.aspose.slides/itrendlinecollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

يمثل مجموعة من TrendlineEx
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد العنصر عند الفهرس المحدد. |
| [getCount()](#getCount--) | يعيد عدد العناصر الفعلية الموجودة في المجموعة. |
| [add(int trendlineType)](#add-int-) | يضيف Trendline جديد في نهاية المجموعة ويعيده. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | يزيل القيمة المحددة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

يعيد العنصر عند الفهرس المحدد. للقراءة فقط [ITrendline](../../com.aspose.slides/itrendline).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

يعيد عدد العناصر الفعلية الموجودة في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

يضيف Trendline جديد في نهاية المجموعة ويعيده.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| trendlineType | int | نوع Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**القيمة المرجعة:**
[ITrendline](../../com.aspose.slides/itrendline) - Trendline جديد [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

يزيل القيمة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline للإزالة [ITrendline](../../com.aspose.slides/itrendline) |