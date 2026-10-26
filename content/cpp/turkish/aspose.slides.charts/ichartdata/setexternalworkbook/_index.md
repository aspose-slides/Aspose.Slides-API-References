---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API Referansı
description: Harita için dış çalışma kitabını veri kaynağı olarak ayarlar. Grafik verileri hedef çalışma kitabından güncellenecektir.
type: docs
weight: 196
url: /tr/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) metodu

Harita için dış çalışma kitabını veri kaynağı olarak ayarlar. [Chart](../../chart/) veri hedef çalışma kitabından güncellenecektir.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### Parametreler

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

## IChartData::SetExternalWorkbook(System::String, bool) metodu

Harita için dış çalışma kitabını veri kaynağı olarak ayarlar.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Hedef çalışma kitabının yolu |
| updateChartData | **bool** | Değer false ise yalnızca çalışma kitabı yolu güncellenecektir. [Chart](../../chart/) veri hedef çalışma kitabından yüklenmeyecek ve güncellenmeyecektir. Hedef çalışma kitabı mevcut olmadığında veya erişilemez olduğunda kullanılabilir. Değer true ise grafik verileri hedef çalışma kitabından güncellenecektir. |
## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [IChartData](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)