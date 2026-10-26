---
title: DataLabelFormat
second_title: Aspose.Sildes .NET API-referencia
description: A DataLabel formázási beállításait képviseli.
type: docs
weight: 1570
url: /hu/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat osztály

A DataLabel formázási beállításait képviseli.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi az IPresentationComponent alap interfész elérését. Csak olvasható [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Visszaadja a diagramot. Csak olvasható [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | A data label formátumát képviseli. Csak olvasható [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Olvasás/írás Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | A DataLabels objektum formátumkarakterláncát képviseli. Olvasás/írás String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | A data label helyzetét képviseli. Olvasás/írás [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Beállít vagy visszaad egy Variant értéket, amely a diagramon a data label-ek elválasztóját jelöli. Olvasás/írás String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Egy adott diagram data label buborékméret érték megjelenítésének viselkedését képviseli. Igaz esetén a buborékméret értéke megjelenik. Hamis esetén rejtett. Olvasás/írás Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Egy adott diagram data label kategórianév megjelenítésének viselkedését képviseli. Igaz esetén a kategórianév megjelenik a diagram data label-jeiben. Hamis esetén rejtett. Olvasás/írás Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Meghatározza, hogy egy adott diagram data label-je adat hívásként vagy adat címkeként jelenik-e meg. Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection gyűjteményben új adatcímkék ShowLabelAsDataCallout tulajdonságának alapértelmezett értékét adja meg vagy állítja be. A tulajdonság értékének beállítása ugyanakkor ezt az értéket a DataLabelCollection gyűjteményben lévő összes adatcímke ShowLabelAsDataCallout tulajdonságára is alkalmazza (például "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" minden DataLabels[i].ShowLabelAsDataCallout értékét val-ra állítja). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Egy adott diagram data label cell érték megjelenítésének viselkedését képviseli. Igaz esetén a cellaérték megjelenik. Hamis esetén rejtett. Olvasás/írás Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Egy adott diagram data label vezetővonalainak megjelenítésének viselkedését képviseli. Igaz esetén a vezetővonalak megjelennek. Hamis esetén rejtett. Olvasás/írás Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Egy adott diagram data label legend kulcs megjelenítésének viselkedését képviseli. Igaz, ha a legend kulcs látható. Olvasás/írás Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Egy adott diagram data label százalékos érték megjelenítésének viselkedését képviseli. Igaz esetén a százalékos érték megjelenik. Hamis esetén rejtett. Olvasás/írás Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Visszaad vagy beállít egy Boolean értéket, amely a diagram data label-jeinek sorozatnév megjelenítésének viselkedését jelzi. Igaz esetén a sorozatnév megjelenik. Hamis esetén rejtett. Olvasás/írás Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Egy adott diagram data label százalékos érték megjelenítésének viselkedését képviseli. Igaz esetén a százalékos érték megjelenik. Hamis esetén rejtett. Olvasás/írás Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Visszaadja a diagram szövegformátumát. Csak olvasható [`IChartTextFormat`](../icharttextformat). |

## Metódusok

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Lásd még

* osztály [PVIObject](../../aspose.slides/pviobject)
* interfész [IDataLabelFormat](../idatalabelformat)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeszerelés [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->