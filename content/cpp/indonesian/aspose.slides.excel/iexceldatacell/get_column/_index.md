---
title: get_Column()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan indeks nol berbasis kolom di lembar kerja tempat sel berada. Hanya baca int32_t.
type: docs
weight: 40
url: /id/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() metode

Mendapatkan indeks nol berbasis kolom di lembar kerja tempat sel berada. Hanya Baca **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Catatan

Contoh:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Lihat Juga

* Kelas [IExcelDataCell](../)
* Ruang Nama [Aspose::Slides::Excel](../../)
* Perpustakaan [Aspose.Slides](../../../)