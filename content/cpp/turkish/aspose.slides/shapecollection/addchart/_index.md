---
title: AddChart()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 66
url: /tr/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metodu


Yeni bir grafiği oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```


### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Eklenecek grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, nokta biriminde. |
| y | **float** | Yeni grafiğin y koordinatı, nokta biriminde. |
| width | **float** | Grafiğin genişliği, nokta biriminde. |
| height | **float** | Grafiğin yüksekliği, nokta biriminde. |

### Dönüş Değeri

Yeni oluşturulan [Charts::IChart](../../../aspose.slides.charts/ichart/).
## Açıklamalar



Aşağıdaki örnek, PowerPoint [Presentation](../../presentation/) içinde Chart nasıl oluşturulacağını gösterir. 
```cpp
// PPTX dosyasını temsil eden Presentation sınıfının bir örneğini oluşturur
auto pres = System::MakeObject<Presentation>();
// İlk slayta erişir
auto slide = pres->get_Slides()->idx_get(0);
// Varsayılan verileriyle bir grafik ekler
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Grafik başlığını ayarlar
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// İlk serinin değerleri göstermesini ayarlar
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Grafik veri sayfası için dizini ayarlar
int32_t defaultWorksheetIndex = 0;
// Grafik veri çalışma sayfasını alır
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Varsayılan oluşturulan serileri ve kategorileri siler
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Yeni seriler ekler
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Yeni kategoriler ekler
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// İlk grafik serisini alır
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Seri verilerini doldurur
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Seri için dolgu rengini ayarlar
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// İkinci grafik serisini alır
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Seri verilerini doldurur
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Seri için dolgu rengini ayarlar
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// İlk etiketi kategori adını gösterecek şekilde ayarlar
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Seriyi üçüncü etiket için değeri gösterecek şekilde ayarlar
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// PPTX dosyasını diske kaydeder
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metodu


Yeni bir grafiği oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```


### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Eklenecek grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, nokta biriminde. |
| y | **float** | Yeni grafiğin y koordinatı, nokta biriminde. |
| width | **float** | Grafiğin genişliği, nokta biriminde. |
| height | **float** | Grafiğin yüksekliği, nokta biriminde. |
| initWithSample | **bool** | Yeni grafiği örnek seri verileri ve ayarlarıyla başlatmak için true; grafiği bir seri olmadan ve yalnızca minimum ayarlarla oluşturmak için false; bu, oluşturmayı daha hızlı yapar. |

### Dönüş Değeri

Yeni oluşturulan [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Diğer Bağlantılar

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)