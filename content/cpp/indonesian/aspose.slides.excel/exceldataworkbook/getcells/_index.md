---
title: GetCells()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil koleksi sel dari buku kerja yang cocok dengan formula yang ditentukan.
type: docs
weight: 14
url: /id/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) metode

Mendapatkan koleksi sel dari buku kerja yang cocok dengan formula yang ditentukan.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Sebuah formula atau ekspresi rentang (mis., "Sheet1!A1:B3") yang digunakan untuk mengidentifikasi sel target. |
| skipHiddenCells | **bool** | Jika **true**, sel tersembunyi (mis., pada baris atau kolom yang disembunyikan) akan dikecualikan dari hasil. |

### Nilai Kembali

Daftar read-only sel yang cocok dengan formula yang ditentukan.

## Catatan



Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [String](../../../system/string/)
* Class [ExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)