---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من مجموعات السلاسل القابلة للجمع.
type: docs
url: /ar/com.aspose.slides/ichartseriesgroupcollection/
---
**جميع الواجهات المُنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

يمثل مجموعة من مجموعات السلاسل القابلة للجمع.

--------------------

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع قابلة للجمع. تم تعريف مجموعات أنواع السلاسل القابلة للجمع ووصفها باستخدام تعداد CombinableSeriesTypesGroup. كما أن كل مجموعة من السلاسل تحتوي على سلاسل يتم رسمها إما على المحاور الأساسية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة). لذا، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأساسي/الثانوي. 2) مجموعة السلاسل تحتوي على بعض خصائص السلاسل المشتركة لكل سلسلة في المجموعة ("series group properties"). "Series group properties" في الفئة ChartSeriesGroup هي قراءة/كتابة. يمكن لكل من "series group properties" أن يكون له تمثيل للقراءة فقط في الفئة ChartSeries.

## الأساليب

| طريقة | الوصف |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | يحصل على مجموعة السلاسل حسب السلسلة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على مجموعة السلاسل حسب الفهرس. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

يحصل على مجموعة السلاسل حسب السلسلة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**القيم المرجعة:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

يحصل على مجموعة السلاسل حسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيم المرجعة:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)