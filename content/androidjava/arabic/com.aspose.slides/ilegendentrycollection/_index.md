---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents legends collection.
type: docs
url: /ar/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

يمثل مجموعة الأساطير.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على خصائص إدخال الأسطورة المقابل لـ Chart.ChartData.Series[0].DataPoints[index] في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; أو المقابل لـ Chart.ChartData.Series[index] للأنواع الأخرى من المخططات. |
| [getCount()](#getCount--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

يحصل على خصائص إدخال الأسطورة المقابل لـ Chart.ChartData.Series[0].DataPoints[index] في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; أو المقابل لـ Chart.ChartData.Series[index] للأنواع الأخرى من المخططات.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعية:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد العناصر الفعلية الموجودة في المجموعة. قراءة فقط int.

**القيمة المرجعية:**
int