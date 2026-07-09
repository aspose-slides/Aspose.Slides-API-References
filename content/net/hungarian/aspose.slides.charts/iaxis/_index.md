---
title: IAxis
second_title: Aspose.Sildes .NET API referenciája
description: Az objektumot kapszulázza, amely egy diagram tengelyét reprezentálja.
type: docs
weight: 1710
url: /hu/aspose.slides.charts/iaxis/
---
## IAxis interfész

Az objektumot kapszulázza, amely egy diagram tengelyét képviseli.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Tulajdonságok

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Megadja a tengely tényleges fő egységét. A tényleges érték lekéréséhez előzőleg hívja meg az IChart.ValidateChartLayout() metódust. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Megadja a tengely tényleges fő egység skáláját. A tényleges érték lekéréséhez előzőleg hívja meg az IChart.ValidateChartLayout() metódust. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Megadja a tengely tényleges maximális értékét. A tényleges érték lekéréséhez előzőleg hívja meg az IChart.ValidateChartLayout() metódust. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Megadja a tengely tényleges alsegységét. A tényleges érték lekéréséhez előzőleg hívja meg az IChart.ValidateChartLayout() metódust. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Megadja a tengely tényleges alegység skáláját. A tényleges érték lekéréséhez előzőleg hívja meg az IChart.ValidateChartLayout() metódust. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Megadja a tengely tényleges minimális értékét. A tényleges érték lekéréséhez előzőleg hívja meg az IChart.ValidateChartLayout() metódust. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | A kategória tengely aggregációs típusát (csoportosítást) reprezentálja. Kategóriára alkalmazandó. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Lehetővé teszi az alap IFormattedTextContainer interfész lekérését. Csak olvasható [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Jelzi, hogy az értéktengely a kategória tengelyt a kategóriák között metszi-e. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem érvényes 3-D diagramokra. Olvasás/írás Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Megadja a legkisebb időegységet, amely a dátum tengelyen megjelenik. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Megadja a csoport szélességét, ha az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. Kategória tengelyekre alkalmazandó. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Megadja a kategória tengely típusát. Olvasás/írás [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | A tengely azon pontját reprezentálja, ahol a merőleges tengely keresztezi azt. Olvasás/írás Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | A megadott tengelyen a másik tengely metszésének CrossType értékét reprezentálja. Olvasás/írás [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Megadja az értéktengely megjelenítési egységeinek méretezési értékét. Olvasás/írás [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | A tengely formátumát reprezentálja. Csak olvasható [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Meghatározza, hogy a tengelynek van-e látható címe. Olvasás/írás Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Jelzi, hogy a tengely fő egységét automatikusan rendeli-e a rendszer. Olvasás/írás Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Jelzi, hogy a maximális értéket automatikusan rendeli-e a rendszer. Olvasás/írás Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Jelzi, hogy a tengely alegységét automatikusan rendeli-e a rendszer. Olvasás/írás Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Jelzi, hogy a minimális értéket automatikusan rendeli-e a rendszer. Olvasás/írás Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Megadja az automatikus overflow bin értékét. Ha hamis, használja az OverflowBin tulajdonságot. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Megadja az automatikus tick label spacing értékét. Ha hamis, használja a TickLabelSpacing tulajdonságot. Olvasás/írás Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Megadja az automatikus tick marks spacing értékét. Ha hamis, használja a TickMarksSpacing tulajdonságot. Olvasás/írás Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Megadja az automatikus underflow bin értékét. Ha hamis, használja az UnderflowBin tulajdonságot. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Jelzi, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. Olvasás/írás Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Jelzi, hogy a formátum összekapcsolt forrásadatokhoz tartozik-e. Olvasás/írás Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Megadja, hogy alkalmazva van-e az overflow bin. Az overflow bin értékének módosításához használja az IsAutomaticOverflowBin és az OverflowBin beállításokat. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. Olvasás/írás Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Megadja, hogy alkalmazva van-e az underflow bin. Az underflow bin értékének módosításához használja az IsAutomaticUnderflowBin és az UnderflowBin beállításokat. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Jelzi, hogy a tengely látható-e. Olvasás/írás Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Megadja a címkék távolságát a tengelytől. Kategória vagy dátumtengelyre alkalmazandó. Az értéknek 0% és 1000% között kell lennie. Olvasás/írás UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | A logaritmikus alapot reprezentálja. Alapértelmezett érték: 10. Olvasás/írás Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | A diagram tengelyének fő rácsvonalainak formátumát reprezentálja. Csak olvasható [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | A megadott tengely fő jelölőpont típusát reprezentálja. Olvasás/írás [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | A dátum vagy értéktengely fő egységeit reprezentálja. Olvasás/írás Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | A dátumtengely fő egység skáláját reprezentálja. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Az értéktengely maximális értékét reprezentálja. Olvasás/írás Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | A diagram tengelyének kisebb rácsvonalainak formátumát reprezentálja. Csak olvasható [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | A megadott tengely kisebb jelölőpont típusát reprezentálja. Olvasás/írás [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | A dátum vagy értéktengely kisebb egységeit reprezentálja. Olvasás/írás Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | A dátumtengely fő egység skáláját reprezentálja. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Az értéktengely minimális értékét reprezentálja. Olvasás/írás Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Az tengelycímkék formátum stringjét reprezentálja. Olvasás/írás String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Megadja a csoportok számát, ha az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. Kategória tengelyekre alkalmazandó. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Megadja az overflow bin egyéni értékét. Alkalmazandó, ha az IsAutomaticOverflowBin hamis, és az IsOverflowBin igaz. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | A tengely pozícióját reprezentálja. Olvasás/írás [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Jelzi, hogy a fő rácsvonalak megjelennek-e. Csak olvasható Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Jelzi, hogy a kisebb rácsvonalak megjelennek-e. Csak olvasható Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | A megadott tengelyen a jelölőcímkék pozícióját reprezentálja. Olvasás/írás [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | A jelölőcímkék forgásszögét reprezentálja. Olvasás/írás Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. Olvasás/írás UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Megadja, hány jelölőpontot kell kihagyni, mielőtt a következő megjelenik. Kategória vagy sor tengelyekre alkalmazandó. Olvasás/írás UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | A tengely címét adja vissza. Csak olvasható [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Megadja az underflow bin egyéni értékét. Alkalmazandó, ha az IsAutomaticUnderflowBin hamis, és az IsUnderflowBin igaz. |

## Metódusok

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Beállítja az IAxis.CategoryAxisType tulajdonságot egy olyan értékkel, amely automatikusan a tengely adatai alapján kerül meghatározásra. |

### Lásd még

* interfész [IFormattedTextContainer](../iformattedtextcontainer)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->