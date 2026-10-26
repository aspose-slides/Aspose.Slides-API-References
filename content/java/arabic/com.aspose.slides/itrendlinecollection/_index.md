---
title: ITrendlineCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
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
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [add(int trendlineType)](#add-int-) | يضيف Trendline جديد في نهاية المجموعة ويعيده. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | يزيل القيمة المحددة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. قراءة فقط [ITrendline](../../com.aspose.slides/itrendline).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قراءة فقط int.

**القيمة المرجعة:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

يضيف Trendline جديد في نهاية المجموعة ويعيده.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| trendlineType | int | نوع Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**القيمة المرجعة:**
[ITrendline](../../com.aspose.slides/itrendline) - خط الاتجاه الجديد [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

يزيل القيمة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline لإزالة [ITrendline](../../com.aspose.slides/itrendline) |