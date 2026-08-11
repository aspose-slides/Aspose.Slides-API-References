---
title: GetCell()
second_title: مرجع API Aspose.Slides للغة C++
description: تسترجع خلية من ورقة العمل المحددة باستخدام فهرسها وإحداثيات الخلية.
type: docs
weight: 27
url: /ar/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) طريقة

تسترجع خلية من ورقة العمل المحددة باستخدام فهرسها وإحداثيات الخلية.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | **int32_t** | فهرس ورقة العمل بصفرية. |
| row | **int32_t** | فهرس الصف بصفرية للخلية. |
| column | **int32_t** | فهرس العمود بصفرية للخلية. |

### قيمة الإرجاع

الخلية في الموقع المحدد.

## ملاحظات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) طريقة

تسترجع خلية من ورقة العمل المحددة باستخدام اسمها وإحداثيات الخلية.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل. |
| row | **int32_t** | فهرس الصف بصفرية للخلية. |
| column | **int32_t** | فهرس العمود بصفرية للخلية. |

### قيمة الإرجاع

الخلية في الموقع المحدد.

## ملاحظات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) طريقة

تسترجع خلية من ورقة العمل المحددة باستخدام فهرسها واسم الخلية بنمط Excel (مثل "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | **int32_t** | فهرس ورقة العمل بصفرية. |
| cellName | [System::String](../../../system/string/) | مرجع الخلية بنمط Excel (مثل "A1", "C5"). |

### قيمة الإرجاع

الخلية في الموقع المحدد.

## ملاحظات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) طريقة

تسترجع خلية من ورقة العمل المحددة باستخدام اسم الخلية بنمط Excel (مثل "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل. |
| cellName | [System::String](../../../system/string/) | مرجع الخلية بنمط Excel (مثل "A1", "C5"). |

### قيمة الإرجاع

الخلية في الموقع المحدد.

## ملاحظات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## أنظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IExcelDataCell](../../iexceldatacell/)
* فئة [ExcelDataWorkbook](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)