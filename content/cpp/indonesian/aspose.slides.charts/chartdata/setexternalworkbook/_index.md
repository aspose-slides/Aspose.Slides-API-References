---
title: SetExternalWorkbook()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan buku kerja eksternal sebagai sumber data untuk diagram. Data diagram akan diperbarui dari buku kerja target.
type: docs
weight: 183
url: /id/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) metode

Menetapkan buku kerja eksternal sebagai sumber data untuk diagram. [Chart](../../chart/) data akan diperbarui dari buku kerja target.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Jalur ke buku kerja target |
## Catatan

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) metode

Menetapkan buku kerja eksternal sebagai sumber data untuk diagram.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Jalur ke buku kerja target |
| updateChartData | **bool** | Jika nilainya false, hanya jalur buku kerja yang akan diperbarui. [Chart](../../chart/) data tidak akan dimuat dan diperbarui dari buku kerja target. Dapat digunakan ketika buku kerja target tidak ada atau tidak tersedia. Jika nilainya true, data diagram akan diperbarui dari buku kerja target. |
## Catatan

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [ChartData](../)
* Ruang nama [Aspose::Slides::Charts](../../)
* Pustaka [Aspose.Slides](../../../)