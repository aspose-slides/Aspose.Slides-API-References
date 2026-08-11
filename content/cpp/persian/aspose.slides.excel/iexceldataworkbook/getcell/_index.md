---
title: GetCell()
second_title: مرجع API Aspose.Slides برای C++
description: سلولی را از worksheet مشخص شده با استفاده از اندیس آن و مختصات سلول بازیابی می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) متد

یک سلول را از worksheet مشخص شده با استفاده از اندیس آن و مختصات سلول برمی‌گرداند.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | **int32_t** | اندیس صفر-پایهٔ worksheet. |
| row | **int32_t** | اندیس صفر-پایهٔ ردیف سلول. |
| column | **int32_t** | اندیس صفر-پایهٔ ستون سلول. |

### مقدار بازگشت

سلول در موقعیت مشخص شده.

## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) متد

یک سلول را از worksheet مشخص شده با استفاده از نام آن و مختصات سلول برمی‌گرداند.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | نام worksheet. |
| row | **int32_t** | اندیس صفر-پایهٔ ردیف سلول. |
| column | **int32_t** | اندیس صفر-پایهٔ ستون سلول. |

### مقدار بازگشت

سلول در موقعیت مشخص شده.

## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) متد

یک سلول را از worksheet مشخص شده با استفاده از اندیس آن و نام سلول به سبک Excel (مانند "B2") برمی‌گرداند.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | **int32_t** | اندیس صفر-پایهٔ worksheet. |
| cellName | [System::String](../../../system/string/) | مرجع سلول به سبک Excel (مانند "A1"، "C5"). |

### مقدار بازگشت

سلول در موقعیت مشخص شده.

## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) متد

یک سلول را از worksheet مشخص شده با استفاده از نام سلول به سبک Excel (مانند "B2") برمی‌گرداند.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | نام worksheet. |
| cellName | [System::String](../../../system/string/) | مرجع سلول به سبک Excel (مانند "A1"، "C5"). |

### مقدار بازگشت

سلول در موقعیت مشخص شده.

## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [IExcelDataWorkbook](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)