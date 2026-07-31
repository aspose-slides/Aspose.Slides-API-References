---
title: GetWorksheetNames()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengambil nama semua lembar kerja yang terdapat dalam buku kerja Excel.
type: docs
weight: 40
url: /id/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() method


Mengambil nama semua lembar kerja yang terdapat dalam buku kerja [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### Nilai Kembali

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
* Kelas [IExcelDataWorkbook](../)
* Ruang Nama [Aspose::Slides::Excel](../../)
* Perpustakaan [Aspose.Slides](../../../)