---
title: DataLabelFormat
second_title: Aspose.Sildes için .NET API Referansı
description: DataLabel için biçimlendirme seçeneklerini temsil eder.
type: docs
weight: 1550
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
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almayı sağlar. Yalnızca okunabilir [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Grafiği döndürür. Yalnızca okunabilir [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Veri etiketinin biçimini temsil eder. Yalnızca okunabilir [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Okunur/yazılır Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | DataLabels nesnesi için biçim dizesini temsil eder. Okunur/yazılır String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Veri etiketinin konumunu temsil eder. Okunur/yazılır [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür. Okunur/yazılır String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Belirtilen grafiğin veri etiketi balon boyutu değerinin gösterim davranışını temsil eder. True değeri balon boyutu değerini gösterir. False değeri gizler. Okunur/yazılır Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Belirtilen grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. True değeri kategori adını gösterir. False değeri gizler. Okunur/yazılır Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Belirtilen grafiğin veri etiketinin veri çağrısı olarak mı yoksa veri etiketi olarak mı görüntüleneceğini belirler. Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowLabelAsDataCallout özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowLabelAsDataCallout özelliğine bu değeri atar (ör. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" tüm DataLabels[i].ShowLabelAsDataCallout değerini val yapar). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Belirtilen grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. True değeri hücre değerini gösterir. False değeri gizler. Okunur/yazılır Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Belirtilen grafiğin veri etiketi lider çizgileri gösterim davranışını temsil eder. True değeri lider çizgileri gösterir. False değeri gizler. Okunur/yazılır Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Belirtilen grafiğin veri etiketi açıklama anahtarı gösterim davranışını temsil eder. True değeri açıklama anahtarının görünür olduğunu gösterir. Okunur/yazılır Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Belirtilen grafiğin veri etiketi yüzde değeri gösterim davranışını temsil eder. True değeri yüzde değerini gösterir. False değeri gizler. Okunur/yazılır Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Grafikteki veri etiketleri için seri adının gösterim davranışını belirten bir Boolean döndürür veya ayarlar. True değeri seri adını gösterir. False değeri gizler. Okunur/yazılır Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Belirtilen grafiğin veri etiketi yüzde değeri gösterim davranışını temsil eder. True değeri yüzde değerini gösterir. False değeri gizler. Okunur/yazılır Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Grafik metin biçimini döndürür. Yalnızca okunabilir [`IChartTextFormat`](../icharttextformat). |

## Yöntemler

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Hash kodunu döndürür. |

### Ayrıca Bakınız

* sınıf [PVIObject](../../aspose.slides/pviobject)
* arayüz [IDataLabelFormat](../idatalabelformat)
* ad uzayı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->