---
title: AddChart
second_title: Aspose.Sildes için .NET API Referansı
description: Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 100
url: /tr/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | ChartType | Eklenecek grafiğin türü. |
| x | Single | Yeni grafiğin x koordinatı, nokta cinsinden. |
| y | Single | Yeni grafiğin y koordinatı, nokta cinsinden. |
| width | Single | Grafiğin genişliği, nokta cinsinden. |
| height | Single | Grafiğin yüksekliği, nokta cinsinden. |

### Dönüş değeri

Yeni oluşturulan [`IChart`](../../../aspose.slides.charts/ichart).

### Örnekler

Aşağıdaki örnek, PowerPoint Sunumu içinde Grafik nasıl oluşturulacağını gösterir.

```csharp
[C#]
// PPTX dosyasını temsil eden Presentation sınıfını örnekler
using(Presentation pres = new Presentation()) {
  // İlk slayta erişir
  ISlide sld = pres.Slides[0];
  // Varsayılan verileriyle bir grafik ekler
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Grafik başlığını ayarlar
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // İlk serinin değerleri göstermesini ayarlar
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Grafik veri sayfası için dizini ayarlar
  int defaultWorksheetIndex = 0;
  // Grafik veri çalışma sayfasını alır
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Varsayılan oluşturulan serileri ve kategorileri siler
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Yeni seriler ekler
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Yeni kategoriler ekler
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // İlk grafik serisini alır
  IChartSeries series = chart.ChartData.Series[0];
  // Seri verilerini doldurur
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Serinin dolgu rengini ayarlar
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // İkinci grafik serisini alır
  series = chart.ChartData.Series[1];
  // Seri verilerini doldurur
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Serinin dolgu rengini ayarlar
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // İlk etiketi Kategori adını gösterecek şekilde ayarlar
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Seriyi üçüncü etiket için değeri gösterecek şekilde ayarlar
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // PPTX dosyasını diske kaydeder
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Ayrıca bakınız

* arayüz [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* sınıf [ShapeCollection](../../shapecollection)
* ad alanı [Aspose.Slides](../../shapecollection)
* derleme [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | ChartType | Eklenecek grafiğin türü. |
| x | Single | Yeni grafiğin x koordinatı, nokta cinsinden. |
| y | Single | Yeni grafiğin y koordinatı, nokta cinsinden. |
| width | Single | Grafiğin genişliği, nokta cinsinden. |
| height | Single | Grafiğin yüksekliği, nokta cinsinden. |
| initWithSample | Boolean | Doğru ise yeni grafik örnek seri verileri ve ayarlarıyla başlatılır; yanlış ise grafik hiçbir seri olmadan ve yalnızca minimum ayarlarla oluşturulur, bu da oluşturmayı hızlandırır. |

### Dönüş değeri

Yeni oluşturulan [`IChart`](../../../aspose.slides.charts/ichart).

### Ayrıca bakınız

* arayüz [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* sınıf [ShapeCollection](../../shapecollection)
* ad alanı [Aspose.Slides](../../shapecollection)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->