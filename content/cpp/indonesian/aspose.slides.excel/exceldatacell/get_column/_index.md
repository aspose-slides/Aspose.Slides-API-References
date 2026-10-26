---
title: get_Column()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan indeks berbasis nol dari kolom di lembar kerja tempat sel berada. Hanya-baca int32_t.
type: docs
weight: 40
url: /id/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() metode


Mendapatkan indeks berbasis nol dari kolom di lembar kerja tempat sel berada. Hanya-baca **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Lihat Juga

* Kelas [ExcelDataCell](../)
* Ruang Nama [Aspose::Slides::Excel](../../)
* Pustaka [Aspose.Slides](../../../)