---
title: get_Row()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan indeks berbasis nol untuk baris di lembar kerja tempat sel berada. Hanya-baca int32_t.
type: docs
weight: 27
url: /id/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() method


Mendapatkan indeks berbasis nol untuk baris di lembar kerja tempat sel berada. Hanya-baca **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Lihat Juga

* Kelas [IExcelDataCell](../)
* Ruang Nama [Aspose::Slides::Excel](../../)
* Pustaka [Aspose.Slides](../../../)