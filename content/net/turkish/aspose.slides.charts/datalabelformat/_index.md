---
title: DataLabelFormat
second_title: Aspose.Sildes for .NET API Referansı
description: DataLabel için biçimlendirme seçeneklerini temsil eder.
type: docs
weight: 1580
url: /tr/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat sınıfı

DataLabel için biçimlendirme seçeneklerini temsil eder.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Özellikler

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arabirimini almaya izin verir. Yalnızca okuma [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Grafiği döndürür. Yalnızca okuma [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Veri etiketinin formatını temsil eder. Yalnızca okuma [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Okuma/yazma Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | DataLabels nesnesi için biçim dizesini temsil eder. Okuma/yazma String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Veri etiketinin konumunu temsil eder. Okuma/yazma [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden bir Variant ayarlar veya döndürür. Okuma/yazma String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Belirli bir grafiğin veri etiketi balon boyutu değerinin görüntülenme davranışını temsil eder. True balon boyutu değerini gösterir. False gizler. Okuma/yazma Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Belirli bir grafiğin veri etiketi kategori adı görüntülenme davranışını temsil eder. True grafikteki veri etiketleri için kategori adını gösterir. False gizler. Okuma/yazma Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Belirli bir grafiğin veri etiketinin veri açıklaması olarak mı yoksa veri etiketi olarak mı gösterileceğini belirler. Bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection ise bu özellik, DataLabelCollection içindeki yeni veri etiketleri için ShowLabelAsDataCallout özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği değerle ayarlamak, aynı değeri DataLabelCollection içindeki tüm veri etiketleri için ShowLabelAsDataCallout özelliğine de atar (ör. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" tüm DataLabels[i].ShowLabelAsDataCallout aynı değeri alır). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Belirli bir grafiğin veri etiketi hücre değeri görüntülenme davranışını temsil eder. True hücre değerini gösterir. False gizler. Okuma/yazma Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Belirli bir grafiğin veri etiketi lider çizgileri görüntülenme davranışını temsil eder. True lider çizgilerini gösterir. False gizler. Okuma/yazma Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Belirli bir grafiğin veri etiketi lejand anahtarı görüntülenme davranışını temsil eder. True veri etiketi lejand anahtarı görünür. Okuma/yazma Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Belirli bir grafiğin veri etiketi yüzde değeri görüntülenme davranışını temsil eder. True yüzde değerini gösterir. False gizler. Okuma/yazma Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Grafikteki veri etiketleri için seri adı görüntülenme davranışını belirten bir Boolean döndürür veya ayarlar. True seri adını gösterir. False gizler. Okuma/yazma Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Belirli bir grafiğin veri etiketi yüzde değeri görüntülenme davranışını temsil eder. True yüzde değerini gösterir. False gizler. Okuma/yazma Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Grafik metin biçimini döndürür. Yalnızca okuma [`IChartTextFormat`](../icharttextformat). |

## Yöntemler

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodunu döndürür. |

### Ayrıca Bakınız

* sınıf [PVIObject](../../aspose.slides/pviobject)
* arayüz [IDataLabelFormat](../idatalabelformat)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->