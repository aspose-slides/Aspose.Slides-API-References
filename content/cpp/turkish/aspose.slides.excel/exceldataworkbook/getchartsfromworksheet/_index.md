---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bir Excel çalışma kitabının belirli çalışma sayfasındaki tüm grafiklerin indeks ve adlarını içeren bir sözlük alır.
type: docs
weight: 40
url: /tr/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) metodu

Belirtilen [Excel](../../) çalışma kitabının belirli çalıştırma sayfasındaki tüm grafiklerin indeks ve adlarını içeren bir sözlük alır.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Grafikleri aramak için çalıştırma sayfasının adı. |

### Dönüş Değeri

Anahtarın grafik indeksi ve değerin grafik adı olduğu bir sözlük.

## Açıklamalar

Örnek:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDictionary](../../../system.collections.generic/idictionary/)
* Sınıf [String](../../../system/string/)
* Sınıf [ExcelDataWorkbook](../)
* Ad Alanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)