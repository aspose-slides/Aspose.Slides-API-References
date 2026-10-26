---
title: GetChartsFromWorksheet()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil kamus yang berisi indeks dan nama semua bagan di lembar kerja yang ditentukan dari buku kerja Excel.
type: docs
weight: 40
url: /id/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) metode


Mengambil kamus yang berisi indeks dan nama semua bagan di lembar kerja yang ditentukan dari buku kerja [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nama lembar kerja untuk mencari bagan. |

### Return Value

A dictionary where the key is the chart index and the value is the chart name.
## Catatan



Contoh: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IDictionary](../../../system.collections.generic/idictionary/)
* Kelas [String](../../../system/string/)
* Kelas [ExcelDataWorkbook](../)
* Ruang Nama [Aspose::Slides::Excel](../../)
* Perpustakaan [Aspose.Slides](../../../)