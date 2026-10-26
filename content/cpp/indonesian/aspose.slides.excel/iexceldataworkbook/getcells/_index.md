---
title: GetCells()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil sekumpulan sel dari workbook yang sesuai dengan formula yang ditentukan.
type: docs
weight: 1
url: /id/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) method

Mengambil sekumpulan sel dari workbook yang sesuai dengan formula yang ditentukan.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Sebuah formula atau ekspresi rentang (mis., \"Sheet1!A1:B3\") yang digunakan untuk mengidentifikasi sel target. |
| skipHiddenCells | **bool** | Jika **true**, sel tersembunyi (mis., pada baris atau kolom tersembunyi) akan dikecualikan dari hasil. |

### Nilai Kembali

Daftar sel baca-saja yang cocok dengan formula yang ditentukan.

## Catatan



Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Kelas [IExcelDataCell](../../iexceldatacell/)
* Kelas [String](../../../system/string/)
* Kelas [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Perpustakaan [Aspose.Slides](../../../)