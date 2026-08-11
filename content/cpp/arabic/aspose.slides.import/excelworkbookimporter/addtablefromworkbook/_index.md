---
title: AddTableFromWorkbook()
second_title: Aspose.Slides للغة C++ مرجع API
description: يسترجع جدولًا من دفتر عمل Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.
type: docs
weight: 14
url: /ar/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method

تسترجع جدولًا من دفتر العمل [Excel](../../../aspose.slides.excel/) المحدد وتضيفه إلى نهاية مجموعة الأشكال المحددة في الإحداثيات المحددة.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعة الأشكال التي سيُضاف إليها الجدول. |
| x | **float** | إحداثي X لتحديد موضع الجدول. |
| y | **float** | إحداثي Y لتحديد موضع الجدول. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | دفتر العمل [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل التي تحتوي على الجدول. |
| cellRange | [System::String](../../../system/string/) | نطاق الخلايا الذي يحدد الجدول (على سبيل المثال، "A1:D10"). |

### قيمة الإرجاع

الجدول الذي تم إضافته إلى مجموعة الأشكال.

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method

تسترجع جدولًا من ملف دفتر العمل [Excel](../../../aspose.slides.excel/) المحدد وتضيفه إلى نهاية مجموعة الأشكال المحددة في الإحداثيات المحددة.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعة الأشكال التي سيُضاف إليها الجدول. |
| x | **float** | إحداثي X لتحديد موضع الجدول. |
| y | **float** | إحداثي Y لتحديد موضع الجدول. |
| workbookPath | [System::String](../../../system/string/) | المسار إلى ملف دفتر العمل [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل التي تحتوي على الجدول. |
| cellRange | [System::String](../../../system/string/) | نطاق الخلايا الذي يحدد الجدول (على سبيل المثال، "A1:D10"). |

### قيمة الإرجاع

الجدول الذي تم إضافته إلى مجموعة الأشكال.

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method

تسترجع جدولًا من ملف دفتر العمل [Excel](../../../aspose.slides.excel/) المحدد وتضيفه إلى نهاية مجموعة الأشكال المحددة في الإحداثيات المحددة.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعة الأشكال التي سيُضاف إليها الجدول. |
| x | **float** | إحداثي X لتحديد موضع الجدول. |
| y | **float** | إحداثي Y لتحديد موضع الجدول. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق يحتوي على بيانات دفتر العمل. |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل التي تحتوي على الجدول. |
| cellRange | [System::String](../../../system/string/) | نطاق الخلايا الذي يحدد الجدول (على سبيل المثال، "A1:D10"). |

### قيمة الإرجاع

الجدول الذي تم إضافته إلى مجموعة الأشكال.

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ITable](../../../aspose.slides/itable/)
* فئة [IShapeCollection](../../../aspose.slides/ishapecollection/)
* فئة [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* فئة [String](../../../system/string/)
* فئة [ExcelWorkbookImporter](../)
* فئة [Stream](../../../system.io/stream/)
* نطاق [Aspose::Slides::Import](../../)
* مكتبة [Aspose.Slides](../../../)