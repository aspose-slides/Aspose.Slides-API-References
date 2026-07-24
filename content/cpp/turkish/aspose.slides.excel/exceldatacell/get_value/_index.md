---
title: get_Value()
second_title: Aspose.Slides for C++ API Referansı
description: Excel hücresinde bulunan değeri alır.
type: docs
weight: 1
url: /tr/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() yöntemi

[Excel](../../) hücresinde bulunan değeri alır.

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [ExcelDataCell](../)
* AdAlanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)