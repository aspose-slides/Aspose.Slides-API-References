---
title: AddTableFromWorkbook()
second_title: مرجع API Aspose.Slides برای C++
description: یک جدول را از کتاب‌کار Excel مشخص‌شده بازیابی می‌کند و در انتهای مجموعهٔ شکل داده‌شده در مختصات مشخص‌شده اضافه می‌نماید.
type: docs
weight: 14
url: /fa/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) متد

یک جدول را از کتاب‌کار [Excel](../../../aspose.slides.excel/) مشخص‌شده بازیابی می‌کند و در انتهای مجموعهٔ شکل داده‌شده در مختصات مشخص‌شده اضافه می‌نماید.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعهٔ شکل‌هایی که جدول به آن اضافه می‌شود. |
| x | **float** | مختصات X برای موقعیت‌یابی جدول. |
| y | **float** | مختصات Y برای موقعیت‌یابی جدول. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | کتاب‌کار [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | نام برگه کاری که جدول را شامل می‌شود. |
| cellRange | [System::String](../../../system/string/) | محدوده سلول‌هایی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

### مقدار بازگشت

جدولی که به مجموعهٔ شکل اضافه شده بود.

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) متد

یک جدول را از فایل کتاب‌کار [Excel](../../../aspose.slides.excel/) مشخص‌شده بازیابی می‌کند و در انتهای مجموعهٔ شکل داده‌شده در مختصات مشخص‌شده اضافه می‌نماید.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعهٔ شکل‌هایی که جدول به آن اضافه می‌شود. |
| x | **float** | مختصات X برای موقعیت‌یابی جدول. |
| y | **float** | مختصات Y برای موقعیت‌یابی جدول. |
| workbookPath | [System::String](../../../system/string/) | مسیر به فایل کتاب‌کار [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | نام برگه کاری که جدول را شامل می‌شود. |
| cellRange | [System::String](../../../system/string/) | محدوده سلول‌هایی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

### مقدار بازگشت

جدولی که به مجموعهٔ شکل اضافه شده بود.

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) متد

یک جدول را از فایل کتاب‌کار [Excel](../../../aspose.slides.excel/) مشخص‌شده بازیابی می‌کند و در انتهای مجموعهٔ شکل داده‌شده در مختصات مشخص‌شده اضافه می‌نماید.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعهٔ شکل‌هایی که جدول به آن اضافه می‌شود. |
| x | **float** | مختصات X برای موقعیت‌یابی جدول. |
| y | **float** | مختصات Y برای موقعیت‌یابی جدول. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک جریان حاوی داده‌های کتاب‌کار. |
| worksheetName | [System::String](../../../system/string/) | نام برگه کاری که جدول را شامل می‌شود. |
| cellRange | [System::String](../../../system/string/) | محدوده سلول‌هایی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

### مقدار بازگشت

جدولی که به مجموعهٔ شکل اضافه شده بود.

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITable](../../../aspose.slides/itable/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)