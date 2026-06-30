---
title: IAxis
second_title: Aspose.Sildes .NET API referencia
description: Átburkolja azt az objektumot, amely egy diagram tengelyét reprezentálja.
type: docs
weight: 1690
url: /hu/aspose.slides.charts/iaxis/
---
## IAxis interfész

Átburkolja azt az objektumot, amely egy diagram tengelyét reprezentálja.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Megadja a tengely tényleges fő egységét. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Megadja a tengely tényleges fő egység skáláját. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Határozza a tengely tényleges legnagyobb értékét. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Határozza a tengely tényleges kisebb egységét. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Határozza a tengely tényleges kisebb egység skáláját. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Határozza a tengely tényleges legkisebb értékét. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Hozzáadja a kategória tengely aggregációs típusát (csoportosítás). Kategóriára alkalmazandó. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Lehetővé teszi az alap IFormattedTextContainer interfész lekérését. Csak olvasás [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Hozzáadja, hogy az érték tengely metszi-e a kategória tengelyt a kategóriák között. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem érvényes 3-D diagramokra. Olvasás/írás Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Határozza a legkisebb időegységet, amely a dátum tengelyen megjelenik. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Határozza a bin szélességet, ha az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. Kategória tengelyekre alkalmazandó. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Határozza a kategória tengely típusát. Olvasás/írás [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Hozzáadja a pontot a tengelyen, ahol a merőleges tengely metszi azt. Olvasás/írás Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Hozzáadja a CrossType-ot a megadott tengelyen, ahol a másik tengely metszi. Olvasás/írás [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Határozza a megjelenítési egységek skálázási értékét az érték tengelyen. Olvasás/írás [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Hozzáadja a tengely formátumát. Csak olvasás [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Meghatározza, hogy a tengelynek látható címe van-e. Olvasás/írás Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Olvasás/írás Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Jelzi, hogy a legnagyobb érték automatikusan van-e hozzárendelve. Olvasás/írás Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Jelzi, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. Olvasás/írás Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Jelzi, hogy a legkisebb érték automatikusan van-e hozzárendelve. Olvasás/írás Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Határozza az automatikus overflow bin értékét. Ha hamis: használja az OverflowBin tulajdonságot. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Határozza az automatikus jelölőcímke távolságértékét. Ha hamis: használja a TickLabelSpacing tulajdonságot. Olvasás/írás Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Határozza az automatikus jelölővonalak távolságértékét. Ha hamis: használja a TickMarksSpacing tulajdonságot. Olvasás/írás Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Határozza az automatikus underflow bin értékét. Ha hamis: használja az UnderflowBin tulajdonságot. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Hozzáadja, hogy az érték tengely skálatípusa logaritmikus-e vagy sem. Olvasás/írás Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Jelzi, hogy a formátum a forrás adatokhoz van-e kapcsolva. Olvasás/írás Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Határozza, hogy a overflow bin alkalmazva van-e. Használja az IsAutomaticOverflowBin és OverflowBin beállításokat az overflow bin értékének módosításához. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Hozzáadja, hogy a MS PowerPoint az adatpontokat utolsótól az elsőig ábrázolja-e. Olvasás/írás Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Határozza, hogy az underflow bin alkalmazva van-e. Használja az IsAutomaticUnderflowBin és UnderflowBin beállításokat az underflow bin értékének módosításához. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Hozzáadja, hogy a tengely látható-e. Olvasás/írás Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Határozza a címkék távolságát a tengelytől. Kategória vagy dátum tengelyre alkalmazandó. Az érték 0% és 1000% között legyen. Olvasás/írás UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Hozzáadja a logaritmikus alapot. Alapértelmezett érték 10. Olvasás/írás Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Hozzáadja a fő rácsvonalak formátumát egy diagram tengelyen. Csak olvasás [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Hozzáadja a fő jelölő jelleg típusát a megadott tengelyen. Olvasás/írás [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Hozzáadja a fő egységeket a dátum vagy érték tengelyen. Olvasás/írás Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Hozzáadja a fő egység skáláját a dátum tengelyen. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Hozzáadja a legnagyobb értéket az érték tengelyen. Olvasás/írás Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Hozzáadja a kisebb rácsvonalak formátumát egy diagram tengelyen. Csak olvasás [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Hozzáadja a kisebb jelölő jelleg típusát a megadott tengelyen. Olvasás/írás [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Hozzáadja a kisebb egységeket a dátum vagy érték tengelyen. Olvasás/írás Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Hozzáadja a fő egység skáláját a dátum tengelyen. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Hozzáadja a legkisebb értéket az érték tengelyen. Olvasás/írás Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Hozzáadja a formátumkarakterláncot az Axis Labels számára. Olvasás/írás String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Határozza a bin-ek számát, ha az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. Kategória tengelyekre alkalmazandó. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Határozza az overflow bin egyéni értékét. Alkalmazandó, ha az IsAutomaticOverflowBin hamis, és az IsOverflowBin igaz. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Hozzáadja a tengely pozícióját. Olvasás/írás [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Hozzáadja, hogy a fő rácsvonalak láthatók-e. Csak olvasás Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Hozzáadja, hogy a kisebb rácsvonalak láthatók-e. Csak olvasás Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Hozzáadja a jelölőcímkék pozícióját a megadott tengelyen. Olvasás/írás [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Hozzáadja a jelölőcímkék forgásszögét. Olvasás/írás Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Határozza, hány jelölőcímkét kell kihagyni a megjelenő címke között. Olvasás/írás UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Határozza, hány jelölővonalat kell kihagyni a következő megjelenése előtt. Kategória vagy sorozat tengelyre alkalmazandó. Olvasás/írás UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Megkapja a tengely címét. Csak olvasás [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Határozza az underflow bin egyéni értékét. Alkalmazandó, ha az IsAutomaticUnderflowBin hamis, és az IsUnderflowBin igaz. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Hozzáállítja az IAxis.CategoryAxisType tulajdonságot egy olyan értékkel, amely a tengely adatai alapján automatikusan kerül meghatározásra. |

### Lásd még

* interfész [IFormattedTextContainer](../iformattedtextcontainer)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->