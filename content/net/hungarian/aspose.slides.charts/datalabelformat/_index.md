---
title: DataLabelFormat
second_title: Aspose.Sildes .NET API-referencia
description: A DataLabel formázási beállításait reprezentálja.
type: docs
weight: 1550
url: /hu/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat osztály

A DataLabel formázási beállításait reprezentálja.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérdezését. Csak olvasható [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Visszaadja a diagramot. Csak olvasható [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | A data label formátumát reprezentálja. Csak olvasható [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Olvasás/írás Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | A DataLabels objektum formátumkarakterláncát reprezentálja. Olvasás/írás String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | A data label pozícióját reprezentálja. Olvasás/írás [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Beállít vagy visszaad egy Variant értéket, amely a diagram adatcímkéjeinek elválasztóját jelöli. Olvasás/írás String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Egy meghatározott diagram adatcímkéjének buborékméret-érték megjelenítési viselkedését reprezentálja. True megjeleníti a buborékméret-értéket. False elrejti. Olvasás/írás Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Egy meghatározott diagram adatcímkéjének kategória név megjelenítési viselkedését reprezentálja. True megjeleníti a kategória nevet. False elrejti. Olvasás/írás Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Megállapítja, hogy egy adott diagram adatcímkéje adatkiemelésként vagy adatcímkeként jelenik meg.  Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az új adatcímkék ShowLabelAsDataCallout tulajdonságának alapértelmezett értékét a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak a beállítása az értékkel szintén beállítja ezt az értéket a ShowLabelAsDataCallout tulajdonságra az összes adatcímkére a DataLabelCollection gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" okozza, hogy minden DataLabels[i].ShowLabelAsDataCallout egyenlő legyen a val értékkel). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Egy meghatározott diagram adatcímkéjének cellaérték megjelenítési viselkedését reprezentálja. True megjeleníti a cellaértéket. False elrejti. Olvasás/írás Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Egy meghatározott diagram adatcímkéjének vezetővonal megjelenítési viselkedését reprezentálja. True megjeleníti a vezetővonalakat. False elrejti. Olvasás/írás Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Egy meghatározott diagram adatcímkéjének jelmagyarázat kulcs megjelenítési viselkedését reprezentálja. True, ha a jelmagyarázat kulcs látható. Olvasás/írás Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Egy meghatározott diagram adatcímkéjének százalékérték megjelenítési viselkedését reprezentálja. True megjeleníti a százalékértéket. False elrejti. Olvasás/írás Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Visszaad vagy beállít egy Boolean értéket, amely jelzi a sorozatnév megjelenítési viselkedését a diagram adatcímkéinél. True megjeleníti a sorozatnevet. False elrejti. Olvasás/írás Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Egy meghatározott diagram adatcímkéjének százalékérték megjelenítési viselkedését reprezentálja. True megjeleníti a százalékértéket. False elrejti. Olvasás/írás Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Visszaadja a diagram szövegformátumát. Csak olvasható [`IChartTextFormat`](../icharttextformat). |

## Metódusok

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hashkódot. |

### Lásd még

* osztály [PVIObject](../../aspose.slides/pviobject)
* interface [IDataLabelFormat](../idatalabelformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->