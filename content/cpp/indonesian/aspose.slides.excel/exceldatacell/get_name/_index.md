---
title: get_Name()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan nama sel data bagan.
type: docs
weight: 14
url: /id/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() metode


Mendapatkan nama sel data bagan.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [ExcelDataCell](../)
* Ruang nama [Aspose::Slides::Excel](../../)
* Pustaka [Aspose.Slides](../../../)