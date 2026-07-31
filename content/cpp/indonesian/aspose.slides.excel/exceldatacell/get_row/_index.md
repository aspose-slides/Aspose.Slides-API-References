---
title: get_Row()
second_title: Aspose.Slides untuk Referensi API C++
description: Mendapatkan indeks berbasis nol baris di lembar kerja tempat sel berada. Baca-saja int32_t.
type: docs
weight: 27
url: /id/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() metode


Gets the zero-based index of the row in the worksheet where the cell is located. Baca-saja **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Keterangan


Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Lihat Juga

* Kelas [ExcelDataCell](../)
* Ruang Nama [Aspose::Slides::Excel](../../)
* Pustaka [Aspose.Slides](../../../)