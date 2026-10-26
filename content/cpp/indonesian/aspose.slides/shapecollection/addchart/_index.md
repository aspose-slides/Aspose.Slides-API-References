---
title: AddChart()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.
type: docs
weight: 66
url: /id/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metode

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Jenis chart yang akan ditambahkan. |
| x | **float** | Koordinat x chart baru, dalam point. |
| y | **float** | Koordinat y chart baru, dalam point. |
| width | **float** | Lebar chart, dalam point. |
| height | **float** | Tinggi chart, dalam point. |

### Nilai Kembali

[Charts::IChart](../../../aspose.slides.charts/ichart/) yang baru dibuat.

## Catatan

Contoh berikut menunjukkan cara membuat Chart di PowerPoint [Presentation](../../presentation/). 
```cpp
// Membuat instance kelas Presentation yang mewakili file PPTX
auto pres = System::MakeObject<Presentation>();
// Mengakses slide pertama
auto slide = pres->get_Slides()->idx_get(0);
// Menambahkan chart dengan data defaultnya
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Mengatur judul chart
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Mengatur seri pertama agar menampilkan nilai
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Mengatur indeks untuk lembar data chart
int32_t defaultWorksheetIndex = 0;
// Mendapatkan lembar kerja data chart
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Menghapus seri dan kategori yang dihasilkan secara default
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Menambahkan seri baru
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Menambahkan kategori baru
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Mengambil seri chart pertama
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Mengisi data seri
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Mengatur warna isi untuk seri
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Mengambil seri chart kedua
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Mengisi data seri
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Mengatur warna isi untuk seri
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Mengatur label pertama agar menampilkan nama Kategori
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Mengatur seri agar menampilkan nilai untuk label ketiga
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Menyimpan file PPTX ke disk
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metode

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Jenis chart yang akan ditambahkan. |
| x | **float** | Koordinat x chart baru, dalam point. |
| y | **float** | Koordinat y chart baru, dalam point. |
| width | **float** | Lebar chart, dalam point. |
| height | **float** | Tinggi chart, dalam point. |
| initWithSample | **bool** | True untuk menginisialisasi chart baru dengan data seri contoh dan pengaturan; false untuk membuat chart tanpa seri dan hanya pengaturan minimal, yang membuat pembuatan lebih cepat. |

### Nilai Kembali

[Charts::IChart](../../../aspose.slides.charts/ichart/) yang baru dibuat.

## Lihat Juga

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChart](../../../aspose.slides.charts/ichart/)
* Kelas [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)