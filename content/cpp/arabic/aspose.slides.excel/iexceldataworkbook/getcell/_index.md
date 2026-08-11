---
title: GetCell()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم باسترجاع خلية من ورقة العمل المحددة باستخدام فهرسها وإحداثيات الخلية.
type: docs
weight: 14
url: /ar/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) طريقة

يقوم باسترجاع خلية من ورقة العمل المحددة باستخدام فهرسها وإحداثيات الخلية.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | **int32_t** | فهرس ورقة العمل يبدأ من الصفر. |
| row | **int32_t** | فهرس الصف للخلية يبدأ من الصفر. |
| column | **int32_t** | فهرس العمود للخلية يبدأ من الصفر. |

### قيمة الإرجاع

الخلية في الموقع المحدد.
## ملاحظات



مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) طريقة

يقوم باسترجاع خلية من ورقة العمل المحددة باستخدام اسمها وإحداثيات الخلية.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل. |
| row | **int32_t** | فهرس الصف للخلية يبدأ من الصفر. |
| column | **int32_t** | فهرس العمود للخلية يبدأ من الصفر. |

### قيمة الإرجاع

الخلية في الموقع المحدد.
## ملاحظات



مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) طريقة

يقوم باسترجاع خلية من ورقة العمل المحددة باستخدام فهرسها واسم الخلية بصيغة Excel (مثل "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | **int32_t** | فهرس ورقة العمل يبدأ من الصفر. |
| cellName | [System::String](../../../system/string/) | مرجع الخلية بصيغة Excel (مثل "A1", "C5"). |

### قيمة الإرجاع

الخلية في الموقع المحدد.
## ملاحظات



مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) طريقة

يقوم باسترجاع خلية من ورقة العمل المحددة باستخدام اسم الخلية بصيغة Excel (مثل "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل. |
| cellName | [System::String](../../../system/string/) | مرجع الخلية بصيغة Excel (مثل "A1", "C5"). |

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

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IExcelDataCell](../../iexceldatacell/)
* فئة [IExcelDataWorkbook](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)