---
title: get_Value()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan nilai yang terkandung dalam sel Excel.
type: docs
weight: 1
url: /id/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() method

Mendapatkan nilai yang terkandung dalam sel [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Keterangan

Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [ExcelDataCell](../)
* Ruang nama [Aspose::Slides::Excel](../../)
* Pustaka [Aspose.Slides](../../../)