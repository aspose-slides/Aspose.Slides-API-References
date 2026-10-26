---
title: get_Column()
second_title: C++ için Aspose.Slides API Referansı
description: Hücrenin bulunduğu çalışma sayfasındaki sütunun sıfır tabanlı indeksini alır. Salt okunur int32_t.
type: docs
weight: 40
url: /tr/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() metod


Çalışma sayfasında hücrenin bulunduğu sütunun sıfır tabanlı indeksini alır. Salt okunur **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Ayrıca Bakınız

* Sınıf [IExcelDataCell](../)
* Ad alanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)