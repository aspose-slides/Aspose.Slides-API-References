---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API Referansı
description: Grafik için dış çalışma kitabını veri kaynağı olarak ayarlar. Grafik verileri hedef çalışma kitabından güncellenecektir.
type: docs
weight: 183
url: /tr/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) yöntemi


Grafik için dış çalışma kitabını veri kaynağı olarak ayarlar. [Chart](../../chart/) verisi hedef çalışma kitabından güncellenecektir.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Hedef çalışma kitabının yolu |
## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) yöntemi


Grafik için dış çalışma kitabını veri kaynağı olarak ayarlar.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Hedef çalışma kitabının yolu |
| updateChartData | **bool** | Eğer değer false ise yalnızca çalışma kitabı yolu güncellenir. [Chart](../../chart/) verisi hedef çalışma kitabından yüklenmez ve güncellenmez. Hedef çalışma kitabı mevcut olmadığında veya erişilemediğinde kullanılabilir. Değer true ise grafik verileri hedef çalışma kitabından güncellenecektir. |
## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [ChartData](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)