---
title: Axis
second_title: Aspose.Sildes a .NET API-referencia
description: Lefedi azt az objektumot, amely egy diagram tengelyét reprezentálja.
type: docs
weight: 1160
url: /hu/aspose.slides.charts/axis/
---
## Axis osztály

Encapsulates the object that represents a chart's axis.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Tulajdonságok

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Meghatározza a tengely tényleges nagy egységét. Hívja meg előzetesen az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Meghatározza a tengely tényleges nagy egység skáláját. Hívja meg előzetesen az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Meghatározza a tengely tényleges legnagyobb értékét. Hívja meg előzetesen az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Meghatározza a tengely tényleges kis egységét. Hívja meg előzetesen az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Meghatározza a tengely tényleges kis egység skáláját. Hívja meg előzetesen az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Meghatározza a tengely tényleges legkisebb értékét. Hívja meg előzetesen az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Ábrázolja a kategória tengely aggregációs típusát (csoportosítás). Kategóriára alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Megadja, hogy az érték tengely a kategória tengelyt a kategóriák között keresztezi-e. Ez a tulajdonság csak a kategória tengelyekre vonatkozik, és nem alkalmazható 3D diagramokra. Olvasás/írás Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Meghatározza a legkisebb időegységet, amely a dátum tengelyen megjelenik. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Meghatározza a bin szélességet, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. Kategória tengelyekre alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Meghatározza a kategória tengely típusát. Olvasás/írás [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Visszaadja a szülő diagramot. Csak olvasható [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Ábrázolja a pontot a tengelyen, ahol a merőleges tengely áthalad rajta. Olvasás/írás Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Ábrázolja a CrossType-ot a megadott tengelyen, ahol a másik tengely keresztezi. Olvasás/írás [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Meghatározza a megjelenítési egységek méretezési értékét az érték tengelyen. Olvasás/írás [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Ábrázolja a tengely formátumát. Csak olvasható [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Megállapítja, hogy a tengelynek látható címe van-e. Olvasás/írás Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Jelzi, hogy a tengely nagy egysége automatikusan van-e kiosztva. Olvasás/írás Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Jelzi, hogy a legnagyobb érték automatikusan van-e kiosztva. Olvasás/írás Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Jelzi, hogy a tengely kis egysége automatikusan van-e kiosztva. Olvasás/írás Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Jelzi, hogy a legkisebb érték automatikusan van-e kiosztva. Olvasás/írás Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Meghatározza az automatikus overflow bin értékét. Ha hamis, használja az OverflowBin tulajdonságot. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Meghatározza az automatikus címke-eltolás értékét. Ha hamis, használja a TickLabelSpacing tulajdonságot. Olvasás/írás Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Meghatározza az automatikus jelölővonal eltolás értékét. Ha hamis, használja a TickMarksSpacing tulajdonságot. Olvasás/írás Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Meghatározza az automatikus underflow bin értékét. Ha hamis, használja az UnderflowBin tulajdonságot. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Ábrázolja, hogy az érték tengely skálatípusa logaritmikus-e vagy sem. Olvasás/írás Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Jelzi, hogy a formátum összekapcsolt forrásadat-e. Olvasás/írás Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Meghatározza, hogy az overflow bin alkalmazva van-e. Használja az IsAutomaticOverflowBin és OverflowBin értékeket az overflow bin értékének módosításához. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Ábrázolja, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. Olvasás/írás Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Meghatározza, hogy az underflow bin alkalmazva van-e. Használja az IsAutomaticUnderflowBin és UnderflowBin értékeket az underflow bin értékének módosításához. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Ábrázolja, hogy a tengely látható-e. Olvasás/írás Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Meghatározza a címkék távolságát a tengelytől. Kategória vagy dátum tengelyre alkalmazott. Az érték 0% és 1000% között kell legyen. Olvasás/írás UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Ábrázolja a logaritmikus alapot. Alapértelmezett érték 10. Olvasás/írás Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Ábrázolja a fő rácsvonalak formátumát a diagram tengelyén. Csak olvasható [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Ábrázolja a fő jelölő típusát a megadott tengelyen. Olvasás/írás [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Ábrázolja a fő egységeket a dátum vagy érték tengelyen. Olvasás/írás Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Ábrázolja a fő egység skáláját a dátum tengelyen. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Ábrázolja a legnagyobb értéket az érték tengelyen. Olvasás/írás Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Ábrázolja a kisebb rácsvonalak formátumát a diagram tengelyén. Csak olvasható [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Ábrázolja a kisebb jelölő típusát a megadott tengelyen. Olvasás/írás [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Ábrázolja a kisebb egységeket a dátum vagy érték tengelyen. Olvasás/írás Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Ábrázolja a fő egység skáláját a dátum tengelyen. Olvasás/írás [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Ábrázolja a legkisebb értéket az érték tengelyen. Olvasás/írás Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Ábrázolja a formátum karakterláncot a tengelycímkékhez. Olvasás/írás String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Meghatározza a bin számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. Kategória tengelyekre alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Meghatározza az overflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticOverflowBin hamis és az IsOverflowBin igaz. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Ábrázolja a tengely pozícióját. Olvasás/írás [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | A fő rácsvonal elrejtéséhez állítsa a MajorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. Csak olvasható Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | A kisebb rácsvonal elrejtéséhez állítsa a MinorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. Csak olvasható Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Ábrázolja a szöveg formátumát. Csak olvasható [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Ábrázolja a jelölt címkék pozícióját a megadott tengelyen. Olvasás/írás [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Ábrázolja a jelölt címkék forgatási szögét. Olvasás/írás Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Meghatározza, hány jelölt címkét hagyjon ki a kirajzolt címkék között. Kategória vagy sorozat tengelyre alkalmazott. Olvasás/írás UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Meghatározza, hány jelölővonalat hagyjon ki a következő előtt. Kategória vagy sorozat tengelyre alkalmazott. Olvasás/írás UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Lekéri a tengely címét. Csak olvasható [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Meghatározza az underflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticUnderflowBin hamis és az IsUnderflowBin igaz. |

## Metódusok

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Beállítja az IAxis.CategoryAxisType tulajdonságot egy olyan értékkel, amely a tengely adatai alapján automatikusan kerül meghatározásra. |

### Kapcsolódó elemek

* osztály [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* osztály [AxesManager](../axesmanager)
* interfész [IAxis](../iaxis)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->