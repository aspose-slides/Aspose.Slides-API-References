---
title: get_Column()
second_title: Aspose.Slides için C++ API Referansı
description: Hücrenin bulunduğu çalışma sayfasındaki sütunun sıfır tabanlı indeksini alır. Salt okunur int32_t.
type: docs
weight: 40
url: /tr/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() metodu

Hücrenin bulunduğu çalışma sayfasındaki sütunun sıfır tabanlı indeksini alır. Salt okunur **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Ayrıca Bakınız

* Sınıf [ExcelDataCell](../)
* Ad alanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)