---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من النقاط التي سيتم رسمها في الشريحة أو العمود الثاني في مخطط شريحة داخل شريحة أو شريحة داخل شريحة مع تقسيم مخصص.
type: docs
url: /ar/com.aspose.slides/ipiesplitcustompointcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

يمثل مجموعة من النقاط التي سيتم رسمها في الشريحة أو العمود الثاني في مخطط شريحة داخل شريحة أو شريحة داخل شريحة مع تقسيم مخصص.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | إرجاع نقطة بيانات المخطط حسب الفهرس. |
| [add(int dataPointIndex)](#add-int-) | إضافة نقطة بيانات بناءً على فهرسها في مجموعة نقاط السلسلة الأصلية. |
| [remove(int dataPointIndex)](#remove-int-) | حذف عنصر من المجموعة حسب فهرسه في مجموعة نقاط السلسلة الأصلية. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

إرجاع نقطة بيانات المخطط حسب الفهرس.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس نقطة البيانات. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات المخطط.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

إضافة نقطة بيانات بناءً على فهرسها في مجموعة نقاط السلسلة الأصلية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| dataPointIndex | int | فهرس نقطة البيانات في مجموعة نقاط السلسلة الأصلية. |
### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

حذف عنصر من المجموعة حسب فهرسه في مجموعة نقاط السلسلة الأصلية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| dataPointIndex | int | فهرس نقطة البيانات في مجموعة نقاط السلسلة الأصلية.. |