---
title: get_Name()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan nama sel data diagram. Hanya baca System::String."
type: docs
weight: 14
url: /id/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() metode


Mendapatkan nama sel data diagram. Hanya baca [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
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
* Kelas [IExcelDataCell](../)
* Ruang Nama [Aspose::Slides::Excel](../../)
* Perpustakaan [Aspose.Slides](../../../)