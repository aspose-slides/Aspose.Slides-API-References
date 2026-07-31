---
title: GetWorksheetNames()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mengambil nama semua lembar kerja yang terdapat dalam buku kerja Excel.
type: docs
weight: 53
url: /id/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() method

Mengambil nama semua lembar kerja yang terdapat dalam buku kerja [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```

### Nilai Kembalian

Daftar nama lembar kerja

## Catatan



Contoh:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IList](../../../system.collections.generic/ilist/)
* Kelas [String](../../../system/string/)
* Kelas [ExcelDataWorkbook](../)
* Ruang nama [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)