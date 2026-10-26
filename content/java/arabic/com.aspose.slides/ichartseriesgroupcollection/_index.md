---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل مجموعة المجموعات من السلاسل القابلة للجمع.
type: docs
url: /ar/com.aspose.slides/ichartseriesgroupcollection/
---
**جميع الواجهات المُنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

يمثل مجموعة من المجموعات المتسلسلة القابلة للدمج.

--------------------

1) يحتوي كل مجموعة من السلاسل على سلاسل ذات أنواع قابلة للجمع. تُعرَّف مجموعات أنواع السلاسل القابلة للجمع وتُوصف باستخدام تعداد CombinableSeriesTypesGroup. كما أن كل مجموعة من السلاسل تحتوي على سلاسل تُرسم إما على المحاور الأولية أو على المحاور الثانوية (ليس كليهما في مجموعة واحدة). لذلك، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأساسي/الثانوي.
2) تحتوي مجموعة السلاسل على بعض خصائص السلاسل التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup هي read/write. يمكن لكل من "خصائص مجموعة السلسلة" أن يكون له تمثيل read-only في فئة ChartSeries.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | يحصل على series group حسب series. |
| [get_Item(int index)](#get-Item-int-) | يحصل على series group حسب الفهرس. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

يحصل على series group حسب series.

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**القيمة المرجعة:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

يحصل على series group حسب الفهرس.

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)