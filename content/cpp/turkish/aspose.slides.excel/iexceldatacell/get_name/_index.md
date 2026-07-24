---
title: get_Name()
second_title: Aspose.Slides for C++ API Referansı
description: "Grafik veri hücresinin adını alır. Yalnızca okunur System::String."
type: docs
weight: 14
url: /tr/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() metodu


Grafik veri hücresinin adını alır. Yalnızca okunur [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [IExcelDataCell](../)
* AdAlanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)