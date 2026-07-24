---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen Excel çalışma kitabının belirtilen çalışma sayfasındaki tüm grafiklerin indekslerini ve adlarını içeren bir sözlük döndürür.
type: docs
weight: 27
url: /tr/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) metodu

Belirtilen [Excel](../../) çalışma kitabının belirtilen çalışma sayfasındaki tüm grafiklerin indekslerini ve adlarını içeren bir sözlük döndürür.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Grafikleri aramak için çalışma sayfasının adı. |

## Dönüş Değeri

Anahtarın grafik indeksi, değerin ise grafik adı olduğu bir sözlük.

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

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDictionary](../../../system.collections.generic/idictionary/)
* Sınıf [String](../../../system/string/)
* Sınıf [IExcelDataWorkbook](../)
* Ad Alanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)