---
title: IPieSplitCustomPointCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من النقاط التي يجب رسمها في الشريحة أو الشريط الثاني في مخطط شريط داخل شريحة أو شريحة داخل شريحة مع تقسيم مخصص.
type: docs
url: /ar/com.aspose.slides/ipiesplitcustompointcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

يمثل مجموعة من النقاط التي يجب رسمها في الشريحة أو الشريط الثاني في مخطط شريط داخل شريحة أو شريحة داخل شريحة مع تقسيم مخصص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | إرجاع نقطة بيانات المخطط حسب الفهرس. |
| [add(int dataPointIndex)](#add-int-) | إضافة نقطة بيانات حسب فهرستها في مجموعة نقاط السلسلة الأصلية. |
| [remove(int dataPointIndex)](#remove-int-) | إزالة العنصر من المجموعة حسب فهرسته في مجموعة نقاط السلسلة الأصلية. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


إرجاع نقطة بيانات المخطط حسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس نقطة البيانات. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات المخطط.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


إضافة نقطة بيانات حسب فهرستها في مجموعة نقاط السلسلة الأصلية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| dataPointIndex | int | فهرس نقطة البيانات في مجموعة نقاط السلسلة الأصلية. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


إزالة العنصر من المجموعة حسب فهرسته في مجموعة نقاط السلسلة الأصلية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| dataPointIndex | int | فهرس نقطة البيانات في مجموعة نقاط السلسلة الأصلية.. |