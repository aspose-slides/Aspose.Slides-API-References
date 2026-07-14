---
title: LegendEntryCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة الأساطير.
type: docs
url: /ar/com.aspose.slides/legendentrycollection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المُطبقة:**  
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)  
```
public class LegendEntryCollection implements ILegendEntryCollection
```

يمثل مجموعة الأساطير.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على خصائص إدخال الأسطورة المقابل لـ Chart.ChartData.Series[0].DataPoints[index] في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ أو المقابل لـ Chart.ChartData.Series[index] لأنواع المخططات الأخرى. |
| [getCount()](#getCount--) | يحصل على عدد إدخالات الأسطورة. |

### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

يحصل على خصائص إدخال الأسطورة المقابل لـ Chart.ChartData.Series[0].DataPoints[index] في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ أو المقابل لـ Chart.ChartData.Series[index] لأنواع المخططات الأخرى.

**المُعاملات:**  
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد إدخالات الأسطورة. للقراءة فقط int.

**الإرجاع:**  
int