---
title: AddChart
second_title: مرجع واجهة برمجة التطبيقات Aspose.Sildes لـ .NET
description: ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 100
url: /ar/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | ChartType | نوع المخطط المراد إضافته. |
| x | Single | الإحداثي x للمخطط الجديد، بالنقاط. |
| y | Single | الإحداثي y للمخطط الجديد، بالنقاط. |
| width | Single | عرض المخطط، بالنقاط. |
| height | Single | ارتفاع المخطط، بالنقاط. |

### قيمة الإرجاع

The newly created [`IChart`](../../../aspose.slides.charts/ichart).

### أمثلة

يوضح المثال التالي كيفية إنشاء مخطط في عرض PowerPoint.

```csharp
[C#]
// ينشئ كائن من الفئة Presentation التي تمثل ملف PPTX
using(Presentation pres = new Presentation()) {
  // يصل إلى الشريحة الأولى
  ISlide sld = pres.Slides[0];
  // يضيف مخططًا ببياناته الافتراضية
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // يحدد عنوان المخطط
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // يضبط السلسلة الأولى لإظهار القيم
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // يحدد الفهرس لورقة بيانات المخطط
  int defaultWorksheetIndex = 0;
  // يحصل على ورقة عمل بيانات المخطط
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // يحذف السلاسل والفئات المولدة افتراضيًا
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // يضيف سلاسل جديدة
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // يضيف فئات جديدة
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // يأخذ السلسلة الأولى للمخطط
  IChartSeries series = chart.ChartData.Series[0];
  // يملء بيانات السلسلة
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // يحدد لون التعبئة للسلسلة
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // يأخذ السلسلة الثانية للمخطط
  series = chart.ChartData.Series[1];
  // يملء بيانات السلسلة
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // يحدد لون التعبئة للسلسلة
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // يضبط التسمية الأولى لإظهار اسم الفئة
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // يضبط السلسلة لإظهار القيمة للتسمية الثالثة
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // يحفظ ملف PPTX إلى القرص
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* واجهة [IChart](../../../aspose.slides.charts/ichart)
* عدد [ChartType](../../../aspose.slides.charts/charttype)
* فئة [ShapeCollection](../../shapecollection)
* نطاق [Aspose.Slides](../../shapecollection)
* تجميع [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | ChartType | نوع المخطط المراد إضافته. |
| x | Single | الإحداثي x للمخطط الجديد، بالنقاط. |
| y | Single | الإحداثي y للمخطط الجديد، بالنقاط. |
| width | Single | عرض المخطط، بالنقاط. |
| height | Single | ارتفاع المخطط، بالنقاط. |
| initWithSample | Boolean | True لتهيئة المخطط الجديد ببيانات سلسلة عينة وإعدادات؛ false لإنشاء المخطط بدون سلاسل ومع إعدادات قليلة فقط، مما يجعل الإنشاء أسرع. |

### قيمة الإرجاع

The newly created [`IChart`](../../../aspose.slides.charts/ichart).

### انظر أيضًا

* واجهة [IChart](../../../aspose.slides.charts/ichart)
* عدد [ChartType](../../../aspose.slides.charts/charttype)
* فئة [ShapeCollection](../../shapecollection)
* نطاق [Aspose.Slides](../../shapecollection)
* تجميع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->