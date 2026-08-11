---
title: AddChartFromWorkbook()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمودار را از کتاب کار اکسل مشخص‌شده بازیابی می‌کند و در انتهای مجموعهٔ شکل داده‌شده در مختصات تعیین‌شده اضافه می‌نماید.
type: docs
weight: 1
url: /fa/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) متد

یک نمودار را از کتاب‌کار [Excel](../../../aspose.slides.excel/) مشخص‌شده بازیابی می‌کند و در انتهای مجموعهٔ شکل‌های داده‌شده در مختصات مشخص‌شده اضافه می‌نماید.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعهٔ شکل‌ای که نمودار به آن اضافه می‌شود. |
| x | **float** | مختصات X برای موقعیت‌یابی نمودار. |
| y | **float** | مختصات Y برای موقعیت‌یابی نمودار. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | کتاب‌کار [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | نام کاربرگ حاوی نمودار. |
| chartIndex | **int32_t** | اندیس صفرمبنا برای شکل نمودار که باید درج شود. این اندیس می‌تواند با استفاده از متد [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) به دست آید. |
| embedAllWorkbook | **bool** | اگر **true** باشد، تمام کتاب‌کار داخل نمودار جاسازی می‌شود؛ اگر **false** باشد، فقط داده‌های نمودار جاسازی می‌شود. |

### مقدار برگشتی

نموداری که به مجموعهٔ شکل اضافه شده است.

## نکات

مثال: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) متد

یک نمودار را از کتاب‌کار [Excel](../../../aspose.slides.excel/) مشخص‌شده بازیابی می‌کند و در انتهای مجموعهٔ شکل‌های داده‌شده در مختصات مشخص‌شده اضافه می‌نماید.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعهٔ شکل‌ای که نمودار به آن اضافه می‌شود. |
| x | **float** | مختصات X برای موقعیت‌یابی نمودار. |
| y | **float** | مختصات Y برای موقعیت‌یابی نمودار. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | کتاب‌کار [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | نام کاربرگ حاوی نمودار. |
| chartName | [System::String](../../../system/string/) | نام نمودار برای اضافه شدن. |
| embedAllWorkbook | **bool** | اگر **true** باشد، تمام کتاب‌کار داخل نمودار جاسازی می‌شود؛ اگر **false** باشد، فقط داده‌های نمودار جاسازی می‌شود. |

### مقدار برگشتی

نموداری که به مجموعهٔ شکل اضافه شده است.

## نکات

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

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) متد

یک نمودار را از کتاب‌کار [Excel](../../../aspose.slides.excel/) مشخص‌شده بازیابی می‌کند و در انتهای مجموعهٔ شکل‌های داده‌شده در مختصات مشخص‌شده اضافه می‌نماید.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعهٔ شکل‌ای که نمودار به آن اضافه می‌شود. |
| x | **float** | مختصات X برای موقعیت‌یابی نمودار. |
| y | **float** | مختصات Y برای موقعیت‌یابی نمودار. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی شامل داده‌های کتاب‌کار. |
| worksheetName | [System::String](../../../system/string/) | نام کاربرگ حاوی نمودار. |
| chartName | [System::String](../../../system/string/) | نام نمودار برای اضافه شدن. |
| embedAllWorkbook | **bool** | اگر **true** باشد، تمام کتاب‌کار داخل نمودار جاسازی می‌شود; اگر **false** باشد، فقط داده‌های نمودار جاسازی می‌شود. |

### مقدار برگشتی

نموداری که به مجموعهٔ شکل اضافه شده است.

## نکات

مثال: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) متد

یک نمودار را از کتاب‌کار [Excel](../../../aspose.slides.excel/) مشخص‌شده بازیابی می‌کند و در انتهای مجموعهٔ شکل‌های داده‌شده در مختصات مشخص‌شده اضافه می‌نماید.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | مجموعهٔ شکل‌ای که نمودار به آن اضافه می‌شود. |
| x | **float** | مختصات X برای موقعیت‌یابی نمودار. |
| y | **float** | مختصات Y برای موقعیت‌یابی نمودار. |
| workbookPath | [System::String](../../../system/string/) | مسیر فایل کتاب‌کاری که شامل نمودار است. |
| worksheetName | [System::String](../../../system/string/) | نام کاربرگ حاوی نمودار. |
| chartName | [System::String](../../../system/string/) | نام نمودار برای اضافه شدن. |
| embedWorkbook | **bool** | اگر **true** باشد، کتاب‌کار داخل نمودار جاسازی می‌شود; اگر **false** باشد، نمودار به کتاب‌کار خارجی پیوند می‌دهد. |

### مقدار برگشتی

نموداری که به مجموعهٔ شکل اضافه شده است.

## نکات

مثال: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChart](../../../aspose.slides.charts/ichart/)
* کلاس [IShapeCollection](../../../aspose.slides/ishapecollection/)
* کلاس [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* کلاس [String](../../../system/string/)
* کلاس [ExcelWorkbookImporter](../)
* کلاس [Stream](../../../system.io/stream/)
* فضای‌نام [Aspose::Slides::Import](../../)
* کتابخانه [Aspose.Slides](../../../)