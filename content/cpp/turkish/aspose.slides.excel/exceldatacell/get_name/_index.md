---
title: get_Name()
second_title: Aspose.Slides for C++ API Referansı
description: Grafik veri hücresinin adını alır.
type: docs
weight: 14
url: /tr/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() metot

Grafik veri hücresinin adını alır.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```

## Diğer Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [ExcelDataCell](../)
* Ad Alanı [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)