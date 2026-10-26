---
title: get_Row()
second_title: Aspose.Slides için C++ API Referansı
description: Hücrenin bulunduğu çalışma sayfasındaki satırın sıfır tabanlı dizinini alır. Salt okunur int32_t.
type: docs
weight: 27
url: /tr/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() yöntemi


Hücrenin bulunduğu çalışma sayfasındaki satırın sıfır tabanlı dizinini alır. Salt okunur **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Diğer Bağlantılar

* Sınıf [IExcelDataCell](../)
* Ad alanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)