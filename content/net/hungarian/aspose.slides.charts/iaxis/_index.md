---
title: IAxis
second_title: Aspose.Sildes .NET API referenciája
description: Lefedi azt az objektumot, amely a diagram tengelyét képviseli.
type: docs
weight: 1720
url: /hu/aspose.slides.charts/iaxis/
---
## IAxis interfész

Lefedi azt az objektumot, amely a diagram tengelyét képviseli.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Meghatározza a tengely tényleges fő egységét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Meghatározza a tengely tényleges fő egység skáláját. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Meghatározza a tengely tényleges legnagyobb értékét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Meghatározza a tengely tényleges alacsony egységét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Meghatározza a tengely tényleges alacsony egység skáláját. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Meghatározza a tengely tényleges legkisebb értékét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | A kategória tengely aggregációs típusát (csoportosítás) jelöli. Kategóriára alkalmazva. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Lehetővé teszi az IFormattedTextContainer alap interfész lekérését. Csak olvasható [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Azt jelzi, hogy az érték tengely metszi-e a kategória tengelyt a kategóriák között. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem érvényes 3D diagramokra. Olvasható/írható Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Meghatározza a legkisebb időegységet, amely a dátum tengelyen megjelenik. Olvasható/írható [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Megadja a bin szélességet, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. Kategória tengelyekre alkalmazva. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Meghatározza a kategória tengely típusát. Olvasható/írható [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | A tengely azon pontját jelöli, ahol a merőleges tengely metszik. Olvasható/írható Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | A megadott tengelyen a CrossType értéket jelöli, ahol a másik tengely metszi. Olvasható/írható [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Meghatározza a megjelenítési egységek méretezési értékét az érték tengelyen. Olvasható/írható [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | A tengely formátumát jelöli. Csak olvasható [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Meghatározza, hogy a tengelynek van-e látható címe. Olvasható/írható Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Azt jelzi, hogy a tengely fő egységét automatikusan rendelik-e. Olvasható/írható Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Azt jelzi, hogy a legnagyobb értéket automatikusan rendelik-e. Olvasható/írható Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Azt jelzi, hogy a tengely alacsony egységét automatikusan rendelik-e. Olvasható/írható Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Azt jelzi, hogy a legkisebb értéket automatikusan rendelik-e. Olvasható/írható Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Megadja az automatikus overflow bin értékét. Ha false: használja az OverflowBin tulajdonságot. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Megadja az automatikus jelölőcímke távolság értékét. Ha false: használja a TickLabelSpacing tulajdonságot. Olvasható/írható Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Megadja az automatikus jelölővonalak távolság értékét. Ha false: használja a TickMarksSpacing tulajdonságot. Olvasható/írható Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Megadja az automatikus underflow bin értékét. Ha false: használja az UnderflowBin tulajdonságot. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Azt jelzi, hogy az érték tengely skálatípusa logaritmikus-e vagy sem. Olvasható/írható Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Azt jelzi, hogy a formátum összekapcsolt forrásadatai vannak-e. Olvasható/írható Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Megadja, hogy alkalmazva van-e az overflow bin. Használja az IsAutomaticOverflowBin és OverflowBin értékeket az overflow bin értékének módosításához. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Azt jelzi, hogy az MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. Olvasható/írható Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Megadja, hogy alkalmazva van-e az underflow bin. Használja az IsAutomaticUnderflowBin és UnderflowBin értékeket az underflow bin értékének módosításához. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Azt jelzi, hogy a tengely látható-e. Olvasható/írható Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Meghatározza a címkék távolságát a tengelytől. Kategória vagy dátum tengelyre alkalmazva. Az értéknek 0 % és 1000 % között kell lennie. Olvasható/írható UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | A logaritmikus alapot jelöli. Alapértelmezett érték 10. Olvasható/írható Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | A diagram tengelyen a fő rácsvonalak formátumát jelöli. Csak olvasható [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | A megadott tengelyen a fő jelölővonal típusát jelöli. Olvasható/írható [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | A dátum vagy érték tengely fő egységeit jelöli. Olvasható/írható Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | A dátum tengely fő egység skáláját jelöli. Olvasható/írható [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | A érték tengely legnagyobb értékét jelöli. Olvasható/írható Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | A diagram tengelyen a kisebb rácsvonalak formátumát jelöli. Csak olvasható [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | A megadott tengelyen a kisebb jelölővonal típusát jelöli. Olvasható/írható [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | A dátum vagy érték tengely kisebb egységeit jelöli. Olvasható/írható Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | A dátum tengely fő egység skáláját jelöli. Olvasható/írható [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | A érték tengely legkisebb értékét jelöli. Olvasható/írható Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Az Axis Labels formátum karakterláncát jelöli. Olvasható/írható String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Megadja a binok számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. Kategória tengelyekre alkalmazva. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Megadja az overflow bin egyéni értékét. Alkalmazva, ha az IsAutomaticOverflowBin tulajdonság hamisra van állítva és az IsOverflowBin tulajdonság igaz. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | A tengely helyzetét jelöli. Olvasható/írható [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Azt jelzi, hogy a fő rácsvonalak megjelennek-e. Csak olvasható Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Azt jelzi, hogy a kisebb rácsvonalak megjelennek-e. Csak olvasható Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | A megadott tengelyen a jelölővonal címkék pozícióját jelöli. Olvasható/írható [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | A jelölőcímkék forgatási szögét jelöli. Olvasható/írható Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Megadja, hány jelölőcímkét hagyjon ki a megjelenített címke előtt. Olvasható/írható UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Megadja, hány jelölővonalat hagyjon ki a következő megjelenítése előtt. Kategória vagy sorozat tengelyre alkalmazva. Olvasható/írható UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | A tengely címét adja vissza. Csak olvasható [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Megadja az underflow bin egyéni értékét. Alkalmazva, ha az IsAutomaticUnderflowBin tulajdonság hamisra van állítva és az IsUnderflowBin tulajdonság igaz. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Beállítja az IAxis.CategoryAxisType tulajdonságot egy értékkel, amelyet a tengely adatok alapján automatikusan határoznak meg. |

### Lásd még

* interfész [IFormattedTextContainer](../iformattedtextcontainer)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->