---
title: AddChartFromWorkbook()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بجلب مخطط من مصنف Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.
type: docs
weight: 1
url: /ar/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) طريقة

يجلب مخططًا من مصنف [Excel](../../../aspose.slides.excel/) المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | **float** | إحداثي X لتحديد موضع المخطط. |
| y | **float** | إحداثي Y لتحديد موضع المخطط. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | المصنف [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل التي تحتوي على المخطط. |
| chartIndex | **int32_t** | الفهرس الصفري للشكل المخطط الذي سيتم إدراجه. يمكن الحصول على هذا الفهرس باستخدام طريقة [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | إذا كان **true**، سيتم تضمين المصنف بالكامل في المخطط؛ إذا كان **false**، سيتم تضمين بيانات المخطط فقط. |

### قيمة الإرجاع

المخطط الذي تمت إضافته إلى مجموعة الأشكال.

## ملاحظات



مثال: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) طريقة

يجلب مخططًا من مصنف [Excel](../../../aspose.slides.excel/) المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | **float** | إحداثي X لتحديد موضع المخطط. |
| y | **float** | إحداثي Y لتحديد موضع المخطط. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | المصنف [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل التي تحتوي على المخطط. |
| chartName | [System::String](../../../system/string/) | اسم المخطط الذي سيُضاف. |
| embedAllWorkbook | **bool** | إذا كان **true**، سيتم تضمين المصنف بالكامل في المخطط؛ إذا كان **false**، سيتم تضمين بيانات المخطط فقط. |

### قيمة الإرجاع

المخطط الذي تمت إضافته إلى مجموعة الأشكال.

## ملاحظات



مثال: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();

System::String worksheetName = u"worksheet name";
auto worksheetCharts = wb->GetChartsFromWorksheet(worksheetName);
for (auto&& chart : worksheetCharts)
{
    System::SharedPtr<ISlide> slide = pres->get_Slides()->AddEmptySlide(pres->get_LayoutSlides()->idx_get(0));
    ExcelWorkbookImporter::AddChartFromWorkbook(slide->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chart.get_Key(), false);
}
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) طريقة

يجلب مخططًا من مصنف [Excel](../../../aspose.slides.excel/) المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | **float** | إحداثي X لتحديد موضع المخطط. |
| y | **float** | إحداثي Y لتحديد موضع المخطط. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق يحتوي على بيانات المصنف. |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل التي تحتوي على المخطط. |
| chartName | [System::String](../../../system/string/) | اسم المخطط الذي سيُضاف. |
| embedAllWorkbook | **bool** | إذا كان **true**، سيتم تضمين المصنف بالكامل في المخطط؛ إذا كان **false**، سيتم تضمين بيانات المخطط فقط. |

### قيمة الإرجاع

المخطط الذي تمت إضافته إلى مجموعة الأشكال.

## ملاحظات



مثال: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) طريقة

يجلب مخططًا من مصنف [Excel](../../../aspose.slides.excel/) المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | **float** | إحداثي X لتحديد موضع المخطط. |
| y | **float** | إحداثي Y لتحديد موضع المخطط. |
| workbookPath | [System::String](../../../system/string/) | مسار الملف إلى المصنف الذي يحتوي على المخطط. |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل التي تحتوي على المخطط. |
| chartName | [System::String](../../../system/string/) | اسم المخطط الذي سيُضاف. |
| embedWorkbook | **bool** | إذا كان **true**، سيتم تضمين المصنف في المخطط؛ إذا كان **false**، سيُربط المخطط بالمصنف الخارجي. |

### قيمة الإرجاع

المخطط الذي تمت إضافته إلى مجموعة الأشكال.

## ملاحظات



مثال: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IChart](../../../aspose.slides.charts/ichart/)
* الفئة [IShapeCollection](../../../aspose.slides/ishapecollection/)
* الفئة [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* الفئة [String](../../../system/string/)
* الفئة [ExcelWorkbookImporter](../)
* الفئة [Stream](../../../system.io/stream/)
* النطاق [Aspose::Slides::Import](../../)
* المكتبة [Aspose.Slides](../../../)