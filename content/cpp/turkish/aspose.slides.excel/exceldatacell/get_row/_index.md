---
title: get_Row()
second_title: Aspose.Slides for C++ API Referansı
description: Hücrenin bulunduğu çalışma sayfasındaki satırın sıfır tabanlı indeksini alır. Yalnızca okunabilir int32_t.
type: docs
weight: 27
url: /tr/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() metodu


Hücrenin bulunduğu çalışma sayfasındaki satırın sıfır tabanlı indeksini alır. Yalnızca okunabilir **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Ayrıca Bakınız

* Sınıf [ExcelDataCell](../)
* Ad Alanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)