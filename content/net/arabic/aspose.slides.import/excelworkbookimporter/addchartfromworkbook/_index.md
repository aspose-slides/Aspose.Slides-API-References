---
title: AddChartFromWorkbook
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يسترجع مخططًا من مصنف Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المحددة في الإحداثيات المحددة.
type: docs
weight: 10
url: /ar/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

يسترجع مخططًا من مصنف Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| معلمة | نوع | الوصف |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | Single | الإحداثي X لتحديد موقع المخطط. |
| y | Single | الإحداثي Y لتحديد موقع المخطط. |
| workbook | IExcelDataWorkbook | مصنف Excel. |
| worksheetName | String | اسم ورقة العمل التي تحتوي على المخطط. |
| chartIndex | Int32 | الفهرس الصفري للمخطط المراد إدراجه. يمكن الحصول على هذا الفهرس باستخدام الطريقة [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet). |
| embedAllWorkbook | Boolean | إذا كان `true`، سيتم تضمين المصنف بالكامل في المخطط؛ إذا كان `false`، سيتم تضمين بيانات المخطط فقط. |

### قيمة الإرجاع

المخطط الذي تم إضافته إلى مجموعة الأشكال.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | يُطرح عندما يكون أي معاملة مطلوبة فارغة أو غير موجودة، أو عندما لا يمكن العثور على المخطط في المصنف. |

### الأمثلة

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

### انظر أيضًا

* الواجهة [IChart](../../../aspose.slides.charts/ichart)
* الواجهة [IShapeCollection](../../../aspose.slides/ishapecollection)
* الواجهة [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* الفئة [ExcelWorkbookImporter](../../excelworkbookimporter)
* النطاق [Aspose.Slides.Import](../../excelworkbookimporter)
* التجميع [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

يسترجع مخططًا من مصنف Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| معلمة | نوع | الوصف |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | Single | الإحداثي X لتحديد موقع المخطط. |
| y | Single | الإحداثي Y لتحديد موقع المخطط. |
| workbook | IExcelDataWorkbook | مصنف Excel. |
| worksheetName | String | اسم ورقة العمل التي تحتوي على المخطط. |
| chartName | String | اسم المخطط الذي سيُضاف. |
| embedAllWorkbook | Boolean | إذا كان `true`، سيتم تضمين المصنف بالكامل في المخطط؛ إذا كان `false`، سيتم تضمين بيانات المخطط فقط. |

### قيمة الإرجاع

المخطط الذي تم إضافته إلى مجموعة الأشكال.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | يُطرح عندما يكون أي معاملة مطلوبة فارغة أو غير موجودة، أو عندما لا يمكن العثور على المخطط في المصنف. |

### الأمثلة

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

### انظر أيضًا

* الواجهة [IChart](../../../aspose.slides.charts/ichart)
* الواجهة [IShapeCollection](../../../aspose.slides/ishapecollection)
* الواجهة [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* الفئة [ExcelWorkbookImporter](../../excelworkbookimporter)
* النطاق [Aspose.Slides.Import](../../excelworkbookimporter)
* التجميع [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

يسترجع مخططًا من مصنف Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| معلمة | نوع | الوصف |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | Single | الإحداثي X لتحديد موقع المخطط. |
| y | Single | الإحداثي Y لتحديد موقع المخطط. |
| workbookStream | Stream | تدفق يحتوي على بيانات المصنف. |
| worksheetName | String | اسم ورقة العمل التي تحتوي على المخطط. |
| chartName | String | اسم المخطط الذي سيُضاف. |
| embedAllWorkbook | Boolean | إذا كان `true`، سيتم تضمين المصنف بالكامل في المخطط؛ إذا كان `false`، سيتم تضمين بيانات المخطط فقط. |

### قيمة الإرجاع

المخطط الذي تم إضافته إلى مجموعة الأشكال.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | يُطرح عندما يكون أي معاملة مطلوبة فارغة أو غير موجودة، أو عندما لا يمكن العثور على المخطط في المصنف. |
| InvalidOperationException | يُطرح عندما تكون البيانات المدخلة بتنسيق غير مدعوم. |

### الأمثلة

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

### انظر أيضًا

* الواجهة [IChart](../../../aspose.slides.charts/ichart)
* الواجهة [IShapeCollection](../../../aspose.slides/ishapecollection)
* الفئة [ExcelWorkbookImporter](../../excelworkbookimporter)
* النطاق [Aspose.Slides.Import](../../excelworkbookimporter)
* التجميع [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

يسترجع مخططًا من مصنف Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| معلمة | نوع | الوصف |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | Single | الإحداثي X لتحديد موقع المخطط. |
| y | Single | الإحداثي Y لتحديد موقع المخطط. |
| workbookPath | String | مسار الملف إلى المصنف الذي يحتوي على المخطط. |
| worksheetName | String | اسم ورقة العمل التي تحتوي على المخطط. |
| chartName | String | اسم المخطط الذي سيُضاف. |
| embedWorkbook | Boolean | إذا كان `true`، سيتم تضمين المصنف في المخطط؛ إذا كان `false`، سيرتبط المخطط بالمصنف الخارجي. |

### قيمة الإرجاع

المخطط الذي تم إضافته إلى مجموعة الأشكال.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | يُطرح عندما يكون أي معاملة مطلوبة فارغة أو غير موجودة، أو عندما لا يمكن العثور على المخطط في المصنف. |
| IOException | يُطرح عندما يحدث خطأ إدخال/إخراج أثناء الوصول إلى الملف. |
| InvalidOperationException | يُطرح عندما تكون البيانات المدخلة بتنسيق غير مدعوم. |

### الأمثلة

مثال:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* الواجهة [IChart](../../../aspose.slides.charts/ichart)
* الواجهة [IShapeCollection](../../../aspose.slides/ishapecollection)
* الفئة [ExcelWorkbookImporter](../../excelworkbookimporter)
* النطاق [Aspose.Slides.Import](../../excelworkbookimporter)
* التجميع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->