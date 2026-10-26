---
title: SetExternalWorkbook()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur buku kerja eksternal sebagai sumber data untuk diagram. Data diagram akan diperbarui dari buku kerja target.
type: docs
weight: 196
url: /id/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) metode

Mengatur buku kerja eksternal sebagai sumber data untuk diagram. [Chart](../../chart/) data akan diperbarui dari buku kerja target.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Path ke buku kerja target |
## Catatan

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) metode

Mengatur buku kerja eksternal sebagai sumber data untuk diagram.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Path ke buku kerja target |
| updateChartData | **bool** | Jika nilai false hanya jalur buku kerja yang akan diperbarui. [Chart](../../chart/) data tidak akan dimuat dan diperbarui dari buku kerja target. Dapat digunakan ketika buku kerja target tidak ada atau tidak tersedia. Jika nilai true data diagram akan diperbarui dari buku kerja target. |
## Catatan

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Lihat Juga

* Class [String](../../../system/string/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)