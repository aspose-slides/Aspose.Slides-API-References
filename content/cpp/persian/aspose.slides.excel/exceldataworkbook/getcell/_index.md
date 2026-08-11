---
title: GetCell()
second_title: مرجع API Aspose.Slides برای C++
description: یک سلول را از کاربرگ مشخص‌شده با استفاده از اندیس و مختصات سلول بازیابی می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) متد

یک سلول را از کاربرگ مشخص‌شده با استفاده از شاخص و مختصات سلول بازیابی می‌کند.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | اندیس صفر پایه کاربرگ. |
| row | **int32_t** | اندیس صفر پایه سطر سلول. |
| column | **int32_t** | اندیس صفر پایه ستون سلول. |

### مقدار بازگشتی

سلول در مکان مشخص شده.
## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) متد

یک سلول را از کاربرگ مشخص‌شده با استفاده از نام آن و مختصات سلول بازیابی می‌کند.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | نام کاربرگ. |
| row | **int32_t** | اندیس صفر پایه سطر سلول. |
| column | **int32_t** | اندیس صفر پایه ستون سلول. |

### مقدار بازگشتی

سلول در مکان مشخص شده.
## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) متد

یک سلول را از کاربرگ مشخص‌شده با استفاده از شاخص و نام سلول به سبک اکسل (به‌عنوان مثال "B2") بازیابی می‌کند.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | اندیس صفر پایه کاربرگ. |
| cellName | [System::String](../../../system/string/) | مرجع سلول به سبک اکسل (به‌عنوان مثال "A1", "C5"). |

### مقدار بازگشتی

سلول در مکان مشخص شده.
## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) متد

یک سلول را از کاربرگ مشخص‌شده با استفاده از نام سلول به سبک اکسل (به‌عنوان مثال "B2") بازیابی می‌کند.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | نام کاربرگ. |
| cellName | [System::String](../../../system/string/) | مرجع سلول به سبک اکسل (به‌عنوان مثال "A1", "C5"). |

### مقدار بازگشتی

سلول در مکان مشخص شده.
## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## مراجع دیگر

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IExcelDataCell](../../iexceldatacell/)
* کلاس [ExcelDataWorkbook](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)