---
title: Axis
second_title: Aspose.Sildes .NET API referencia
description: Befoglalja azt az objektumot, amely egy diagram tengelyét reprezentálja.
type: docs
weight: 1180
url: /hu/aspose.slides.charts/axis/
---
## Axis osztály

Befoglalja azt az objektumot, amely egy diagram tengelyét reprezentálja.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Meghatározza a tengely tényleges fő egységét. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Meghatározza a tengely tényleges fő egység skáláját. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Meghatározza a tengely tényleges legnagyobb értékét. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Meghatározza a tengely tényleges kisebb egységét. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Meghatározza a tengely tényleges kisebb egység skáláját. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Meghatározza a tengely tényleges legkisebb értékét. Előzőleg hívja meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | A kategória tengely aggregáció típusát (csoportosítás) képviseli. Alkalmazott a kategóriára. Csak Histogram vagy HistogramPareto sorozatoknál használható. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Megadja, hogy az értéktengely áthalad-e a kategóriatengelyen a kategóriák között. Ez a tulajdonság csak kategóriatengelyekre vonatkozik, és nem alkalmazható 3D diagramokra. Olvasás/írás Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Meghatározza a legkisebb időegységet, amely a dátumtengelyen megjelenik. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Meghatározza a bin (csoport) szélességét, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth-re van beállítva. Alkalmazott kategóriatengelyekre. Csak Histogram vagy HistogramPareto sorozatoknál használható. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Meghatározza a kategóriatengely típusát. Olvasás/írás [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Visszaadja a szülő diagramot. Csak olvasható [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | A tengelyen azt a pontot jelöli, ahol a merőleges tengely áthalad rajta. Olvasás/írás Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | A megadott tengelyen a másik tengely áthaladásának CrossType-ját jelöli. Olvasás/írás [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Meghatározza az értéktengely megjelenítési egységeinek méretezési értékét. Olvasás/írás [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | A tengely formátumát jelöli. Csak olvasható [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Meghatározza, hogy a tengelynek van-e látható címe. Olvasás/írás Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Olvasás/írás Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Jelzi, hogy a legnagyobb érték automatikusan van-e hozzárendelve. Olvasás/írás Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Jelzi, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. Olvasás/írás Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Jelzi, hogy a legkisebb érték automatikusan van-e hozzárendelve. Olvasás/írás Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Meghatározza az automatikus overflow bin (túlcsordulási) értékét. Ha false: használja az OverflowBin tulajdonságot. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Meghatározza az automatikus jelölócímke távolság értékét. Ha false: használja a TickLabelSpacing tulajdonságot. Olvasás/írás Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Meghatározza az automatikus jelölővonalköz közti távolság értékét. Ha false: használja a TickMarksSpacing tulajdonságot. Olvasás/írás Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Meghatározza az automatikus underflow bin (alulcsordulási) értékét. Ha false: használja az UnderflowBin tulajdonságot. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Jelzi, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. Olvasás/írás Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Jelzi, hogy a formátum összekapcsolt forrásadat-e. Olvasás/írás Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Megadja, hogy az overflow bin alkalmazva van-e. Használja az IsAutomaticOverflowBin és az OverflowBin értékeket az overflow bin érték beállításához. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. Olvasás/írás Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Megadja, hogy az underflow bin alkalmazva van-e. Használja az IsAutomaticUnderflowBin és az UnderflowBin értékeket az underflow bin érték beállításához. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Jelzi, hogy a tengely látható-e. Olvasás/írás Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Meghatározza a címkék távolságát a tengelytől. Alkalmazott kategória vagy dátumtengelyre. Az értéknek 0% és 1000% között kell lennie. Olvasás/írás UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | A logaritmikus alapot jelöli. Alapértelmezett érték 10. Olvasás/írás Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | A diagram tengelyének fő rácsvonalak formátumát jelöli. Csak olvasható [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | A megadott tengely fő jelölőjelek típusát jelöli. Olvasás/írás [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | A dátum vagy értéktengely fő egységeit jelöli. Olvasás/írás Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | A dátumtengely fő egység skáláját jelöli. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | A értéktengely legnagyobb értékét jelöli. Olvasás/írás Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | A diagram tengelyének kisebb rácsvonalak formátumát jelöli. Csak olvasható [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | A megadott tengely kisebb jelölőjelek típusát jelöli. Olvasás/írás [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | A dátum vagy értéktengely kisebb egységeit jelöli. Olvasás/írás Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | A dátumtengely fő egység skáláját jelöli. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | A értéktengely legkisebb értékét jelöli. Olvasás/írás Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | A tengelycímkék formátumkarakterláncát jelöli. Olvasás/írás String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Meghatározza a bin-ek számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins-re van beállítva. Alkalmazott kategóriatengelyekre. Csak Histogram vagy HistogramPareto sorozatoknál használható. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Megadja az overflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticOverflowBin tulajdonság false-ra van beállítva és az IsOverflowBin tulajdonság true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | A tengely pozícióját jelöli. Olvasás/írás [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | A fő rácsvonal elrejtéséhez állítsa a MajorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. Csak olvasható Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | A kisebb rácsvonal elrejtéséhez állítsa a MinorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. Csak olvasható Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | A szöveg formátumát jelöli. Csak olvasható [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | A megadott tengelyen a jelölőcímkék helyzetét jelöli. Olvasás/írás [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | A jelölőcímkék forgatás szögét jelöli. Olvasás/írás Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. Alkalmazott kategória vagy sorozattengelyre. Olvasás/írás UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Megadja, hány jelölővonalat kell kihagyni a következő megjelenítése előtt. Alkalmazott kategória vagy sorozattengelyre. Olvasás/írás UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Lekéri a tengely címét. Csak olvasható [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Megadja az underflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticUnderflowBin tulajdonság false-ra van beállítva és az IsUnderflowBin tulajdonság true. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Beállítja az IAxis.CategoryAxisType tulajdonságot egy olyan értékkel, amely automatikusan kerül meghatározásra a tengely adatai alapján. |

### Lásd még

* osztály [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* osztály [AxesManager](../axesmanager)
* interfész [IAxis](../iaxis)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->