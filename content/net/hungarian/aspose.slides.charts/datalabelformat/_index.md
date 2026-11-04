---
title: DataLabelFormat
second_title: Aspose.Sildes .NET API Referencia
description: A DataLabel formázási beállításait reprezentálja.
type: docs
weight: 1580
url: /hu/aspose.slides.charts/datalabelformat/
---
# DataLabelFormat osztály

A DataLabel formázási beállításait reprezentálja.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a bázis IPresentationComponent interfész lekérdezését. Csak olvasható [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Visszaadja a diagramot. Csak olvasható [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | A data label formátumát képviseli. Csak olvasható [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Olvasás/írás Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | A DataLabels objektum formátumkarakterláncát képviseli. Olvasás/írás String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | A data label pozícióját képviseli. Olvasás/írás [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Beállítja vagy adja vissza a diagramon a data label-ek elválasztóját képviselő Variant értéket. Olvasás/írás String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Meghatározza, hogy egy adott diagram adatcímkéjének buborékméret-értéke megjelenjen-e. True megjeleníti a buborékméret-értéket, False elrejti. Olvasás/írás Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Meghatározza, hogy egy adott diagram adatcímkéjének kategórianév legyen-e látható. True megjeleníti a kategórianév, False elrejti. Olvasás/írás Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Meghatározza, hogy a megadott diagram adatcímkéje adatfelhívásként vagy adatcímkeként jelenik meg. Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékével történő beállítás ugyanazt az értéket állítja be a ShowLabelAsDataCallout tulajdonságnak minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" mindegyik DataLabels[i].ShowLabelAsDataCallout értéke ekkor val lesz). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Meghatározza, hogy egy adott diagram adatcímkéjének cellaértéke megjelenjen-e. True megjeleníti a cellaértéket, False elrejti. Olvasás/írás Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Meghatározza, hogy egy adott diagram adatcímkéjének vezető vonalai megjelenjenek-e. True megjeleníti a vezető vonalakat, False elrejti. Olvasás/írás Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Meghatározza, hogy egy adott diagram adatcímkéjének jelmagyarázat-ikona látható-e. True, ha a jelmagyarázat-ikona látható. Olvasás/írás Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Meghatározza, hogy egy adott diagram adatcímkéjének százalékértéke megjelenjen-e. True megjeleníti a százalékértéket, False elrejti. Olvasás/írás Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Visszaadja vagy állítja be, hogy a diagramon a sorozat neve megjelenjen-e a data label-eknél. True megjeleníti a sorozat nevét, False elrejti. Olvasás/írás Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Meghatározza, hogy egy adott diagram adatcímkéjének százalékértéke megjelenjen-e. True megjeleníti a százalékértéket, False elrejti. Olvasás/írás Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Visszaadja a diagram szövegformátumát. Csak olvasható [`IChartTextFormat`](../icharttextformat). |

## Módszerek

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Lásd még

* osztály [PVIObject](../../aspose.slides/pviobject)
* interfész [IDataLabelFormat](../idatalabelformat)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->