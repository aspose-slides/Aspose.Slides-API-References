---
title: GetChartsFromWorksheet()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil kamus yang berisi indeks dan nama semua diagram dalam lembar kerja yang ditentukan pada workbook Excel.
type: docs
weight: 27
url: /id/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) metode

Mendapatkan kamus yang berisi indeks dan nama semua diagram di lembar kerja yang ditentukan dalam workbook [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nama lembar kerja untuk mencari diagram. |

### Nilai Kembali

Sebuah kamus di mana kunci adalah indeks diagram dan nilai adalah nama diagram.
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
* Kelas [IExcelDataWorkbook](../)
* Ruang nama [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)