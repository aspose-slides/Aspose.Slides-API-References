---
title: AddChartFromWorkbook
second_title: Aspose.Sildes برای .NET مرجع API
description: یک نمودار را از کتاب‌کار Excel مشخص‌شده استخراج می‌کند و در انتهای مجموعهٔ شکل‌های داده‌شده در مختصات تعیین‌شده اضافه می‌نماید.
type: docs
weight: 10
url: /fa/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

یک نمودار را از کتاب کار Excel مشخص شده بازیابی می‌کند و در انتهای مجموعهٔ شکل‌های داده شده در مختصات مشخص‌شده اضافه می‌نماید.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعهٔ شکل‌هایی که نمودار به آن اضافه می‌شود. |
| x | Single | مختصات X برای موقعیت‌یابی نمودار. |
| y | Single | مختصات Y برای موقعیت‌یابی نمودار. |
| workbook | IExcelDataWorkbook | کتاب کار Excel. |
| worksheetName | String | نام کاربرگی که نمودار در آن قرار دارد. |
| chartIndex | Int32 | اندیس صفر-مبنای شکل نمودار برای درج. این اندیس می‌تواند با استفاده از روش [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet) به دست آید. |
| embedAllWorkbook | Boolean | اگر `true` باشد، کل کتاب کار در نمودار تعبیه می‌شود؛ اگر `false` باشد، فقط داده‌های نمودار تعبیه می‌شود. |

### مقدار بازگشت

نموداری که به مجموعهٔ شکل‌ها اضافه شده بود.

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentException | زمانی پرتاب می‌شود که هر پارامتر الزامی تهی، خالی باشد یا اگر نمودار نتواند در کتاب کار پیدا شود. |

### مثال‌ها

مثال:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### مراجع

* رابط [IChart](../../../aspose.slides.charts/ichart)
* رابط [IShapeCollection](../../../aspose.slides/ishapecollection)
* رابط [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* کلاس [ExcelWorkbookImporter](../../excelworkbookimporter)
* فضای نام [Aspose.Slides.Import](../../excelworkbookimporter)
* مجموعه [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

یک نمودار را از کتاب کار Excel مشخص شده بازیابی می‌کند و در انتهای مجموعهٔ شکل‌های داده شده در مختصات مشخص‌شده اضافه می‌نماید.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعهٔ شکل‌هایی که نمودار به آن اضافه می‌شود. |
| x | Single | مختصات X برای موقعیت‌یابی نمودار. |
| y | Single | مختصات Y برای موقعیت‌یابی نمودار. |
| workbook | IExcelDataWorkbook | کتاب کار Excel. |
| worksheetName | String | نام کاربرگی که نمودار در آن قرار دارد. |
| chartName | String | نام نموداری که باید اضافه شود. |
| embedAllWorkbook | Boolean | اگر `true` باشد، کل کتاب کار در نمودار تعبیه می‌شود؛ اگر `false` باشد، فقط داده‌های نمودار تعبیه می‌شود. |

### مقدار بازگشت

نموداری که به مجموعهٔ شکل‌ها اضافه شده بود.

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentException | زمانی پرتاب می‌شود که هر پارامتر الزامی تهی، خالی باشد یا اگر نمودار نتواند در کتاب کار پیدا شود. |

### مثال‌ها

مثال:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    string worksheetName = "worksheet name";
    var worksheetCharts = wb.GetChartsFromWorksheet(worksheetName);
    foreach (var chart in worksheetCharts)
    {
        ISlide slide = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);
        ExcelWorkbookImporter.AddChartFromWorkbook(slide.Shapes, 10, 10, wb, worksheetName, chart.Key, false);
    }
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### مراجع

* رابط [IChart](../../../aspose.slides.charts/ichart)
* رابط [IShapeCollection](../../../aspose.slides/ishapecollection)
* رابط [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* کلاس [ExcelWorkbookImporter](../../excelworkbookimporter)
* فضای نام [Aspose.Slides.Import](../../excelworkbookimporter)
* مجموعه [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

یک نمودار را از کتاب کار Excel مشخص شده بازیابی می‌کند و در انتهای مجموعهٔ شکل‌های داده شده در مختصات مشخص‌شده اضافه می‌نماید.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعهٔ شکل‌هایی که نمودار به آن اضافه می‌شود. |
| x | Single | مختصات X برای موقعیت‌یابی نمودار. |
| y | Single | مختصات Y برای موقعیت‌یابی نمودار. |
| workbookStream | Stream | جریانی حاوی داده‌های کتاب کار. |
| worksheetName | String | نام کاربرگی که نمودار در آن قرار دارد. |
| chartName | String | نام نموداری که باید اضافه شود. |
| embedAllWorkbook | Boolean | اگر `true` باشد، کل کتاب کار در نمودار تعبیه می‌شود؛ اگر `false` باشد، فقط داده‌های نمودار تعبیه می‌شود. |

### مقدار بازگشت

نموداری که به مجموعهٔ شکل‌ها اضافه شده بود.

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentException | زمانی پرتاب می‌شود که هر پارامتر الزامی تهی، خالی باشد یا اگر نمودار نتواند در کتاب کار پیدا شود. |
| InvalidOperationException | زمانی پرتاب می‌شود که داده‌های ورودی در قالب پشتیبانی‌شده نیست. |

### مثال‌ها

مثال:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### مراجع

* رابط [IChart](../../../aspose.slides.charts/ichart)
* رابط [IShapeCollection](../../../aspose.slides/ishapecollection)
* کلاس [ExcelWorkbookImporter](../../excelworkbookimporter)
* فضای نام [Aspose.Slides.Import](../../excelworkbookimporter)
* مجموعه [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

یک نمودار را از کتاب کار Excel مشخص شده بازیابی می‌کند و در انتهای مجموعهٔ شکل‌های داده شده در مختصات مشخص‌شده اضافه می‌نماید.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعهٔ شکل‌هایی که نمودار به آن اضافه می‌شود. |
| x | Single | مختصات X برای موقعیت‌یابی نمودار. |
| y | Single | مختصات Y برای موقعیت‌یابی نمودار. |
| workbookPath | String | مسیر فایل به کتاب کاری که شامل نمودار است. |
| worksheetName | String | نام کاربرگی که نمودار در آن قرار دارد. |
| chartName | String | نام نموداری که باید اضافه شود. |
| embedWorkbook | Boolean | اگر `true` باشد، کتاب کار در نمودار تعبیه می‌شود؛ اگر `false` باشد، نمودار به کتاب کار خارجی پیوند خواهد داشت. |

### مقدار بازگشت

نموداری که به مجموعهٔ شکل‌ها اضافه شده بود.

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentException | زمانی پرتاب می‌شود که هر پارامتر الزامی تهی، خالی باشد یا اگر نمودار نتواند در کتاب کار پیدا شود. |
| IOException | زمانی پرتاب می‌شود که هنگام دسترسی به فایل خطای I/O رخ دهد. |
| InvalidOperationException | زمانی پرتاب می‌شود که داده‌های ورودی در قالب پشتیبانی‌شده نیست. |

### مثال‌ها

مثال:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### مراجع

* رابط [IChart](../../../aspose.slides.charts/ichart)
* رابط [IShapeCollection](../../../aspose.slides/ishapecollection)
* کلاس [ExcelWorkbookImporter](../../excelworkbookimporter)
* فضای نام [Aspose.Slides.Import](../../excelworkbookimporter)
* مجموعه [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->