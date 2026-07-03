---
title: AddChart
second_title: مرجع API Aspose.Sildes برای .NET
description: یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌نماید.
type: docs
weight: 100
url: /fa/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | ChartType | نوع نموداری که باید اضافه شود. |
| x | Single | مختصات x نمودار جدید، بر حسب پوینت. |
| y | Single | مختصات y نمودار جدید، بر حسب پوینت. |
| width | Single | عرض نمودار، بر حسب پوینت. |
| height | Single | ارتفاع نمودار، بر حسب پوینت. |

### مقدار بازگشت

مورد تازه ایجاد شده [`IChart`](../../../aspose.slides.charts/ichart).

### مثال‌ها

مثال زیر نشان می‌دهد چگونه یک Chart در یک ارائه PowerPoint ایجاد شود.

```csharp
[C#]
// یک نمونه از کلاس Presentation که نمایانگر یک فایل PPTX است
using(Presentation pres = new Presentation()) {
  // به اولین اسلاید دسترسی می‌یابد
  ISlide sld = pres.Slides[0];
  // یک نمودار با داده‌های پیش‌فرض آن اضافه می‌کند
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // عنوان نمودار را تنظیم می‌کند
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // سری اول را برای نمایش مقادیر تنظیم می‌کند
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // شاخص برگه داده‌های نمودار را تنظیم می‌کند
  int defaultWorksheetIndex = 0;
  // برگه کاری داده‌های نمودار را دریافت می‌کند
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // سری‌ها و دسته‌بندی‌های تولید شده به‌صورت پیش‌فرض را حذف می‌کند
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // سری‌های جدید را اضافه می‌کند
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // دسته‌بندی‌های جدید را اضافه می‌کند
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // اولین سری نمودار را می‌گیرد
  IChartSeries series = chart.ChartData.Series[0];
  // داده‌های سری را پر می‌کند
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // رنگ پر کردن برای سری را تنظیم می‌کند
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // دومین سری نمودار را می‌گیرد
  series = chart.ChartData.Series[1];
  // داده‌های سری را پر می‌کند
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // رنگ پر کردن برای سری را تنظیم می‌کند
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // اولین برچسب را برای نمایش نام دسته تنظیم می‌کند
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // سری را تنظیم می‌کند تا مقدار را برای برچسب سوم نشان دهد
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // فایل PPTX را روی دیسک ذخیره می‌کند
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### موارد مرتبط

* رابط [IChart](../../../aspose.slides.charts/ichart)
* شمارۀ [ChartType](../../../aspose.slides.charts/charttype)
* کلاس [ShapeCollection](../../shapecollection)
* فضای‌نام [Aspose.Slides](../../shapecollection)
* مجوعه [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | ChartType | نوع نموداری که باید اضافه شود. |
| x | Single | مختصات x نمودار جدید، بر حسب پوینت. |
| y | Single | مختصات y نمودار جدید، بر حسب پوینت. |
| width | Single | عرض نمودار، بر حسب پوینت. |
| height | Single | ارتفاع نمودار، بر حسب پوینت. |
| initWithSample | Boolean | True برای مقداردهی اولیه نمودار جدید با داده‌ها و تنظیمات نمونه؛ false برای ایجاد نمودار بدون سری و فقط تنظیمات حداقل، که باعث سرعت بیشتر ایجاد می‌شود. |

### مقدار بازگشت

مورد تازه ایجاد شده [`IChart`](../../../aspose.slides.charts/ichart).

### موارد مرتبط

* رابط [IChart](../../../aspose.slides.charts/ichart)
* شمارۀ [ChartType](../../../aspose.slides.charts/charttype)
* کلاس [ShapeCollection](../../shapecollection)
* فضای‌نام [Aspose.Slides](../../shapecollection)
* مجوعه [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->