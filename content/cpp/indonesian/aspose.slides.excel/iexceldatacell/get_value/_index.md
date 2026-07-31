---
title: get_Value()
second_title: Aspose.Slides untuk Referensi API C++
description: "Mendapatkan nilai yang terkandung dalam sel Excel. Hanya-baca System::Object."
type: docs
weight: 1
url: /id/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() metode


Mendapatkan nilai yang terkandung dalam sel [Excel](../../). Hanya-baca [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [IExcelDataCell](../)
* Ruang Nama [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)