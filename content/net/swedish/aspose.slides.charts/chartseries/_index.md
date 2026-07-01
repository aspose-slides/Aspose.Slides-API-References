---
title: ChartSeries
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en diagramserie.
type: docs
weight: 1420
url: /sv/aspose.slides.charts/chartseries/
---
## ChartSeries-klass

Representerar en diagramserie.

```csharp
public class ChartSeries : IChartSeries
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Anger formen på en serie i ett 3-D stapeldiagram. Ändring av detta egenskapsvärde kan automatiskt ändra typen av serien. Läs/skriv [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Anger hur bubbelstorleksvärden representeras i bubbeldiagrammet. Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till föräldragruppen. Använd ParentSeriesGroup.BubbleSizeRepresentation för att läsa/skriva och ändra värdet. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 % av standardstorleken). Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till föräldragruppen. Använd ParentSeriesGroup.BubbleSizeScale för att läsa/skriva och ändra värdet. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Returnerar det överordnade diagrammet. Skrivskyddad [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Returnerar samlingen av datapunkter för denna serie. Skrivskyddad [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Anger storleken på hålet i ett donutdiagram (kan vara mellan 10 och 90 % av plotområdets storlek). Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till föräldragruppen. Använd ParentSeriesGroup.DoughnutHoleSize för att läsa/skriva och ändra värdet. Skrivskyddad Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Representerar felstaplar för serien med riktning X. Felstaplar med X-riktning är tillgängliga för serier av typ area, bar, scatter och bubble. För alla andra diagramtyper returnerar egenskapen null (inklusive 3D-diagram). Vid anpassade värden används samlingen DataPoints för att ange värdet (med [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)-egenskapen). Skrivskyddad [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Representerar felstaplar för serien med riktning Y. Felstaplar med Y-riktning är tillgängliga för serier av typ area, bar, line, scatter och bubble. För alla andra diagramtyper returnerar egenskapen null (inklusive 3D-diagram). Vid anpassade värden används samlingen DataPoints för att ange värdet (med [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)-egenskapen). Skrivskyddad [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Avståndet för en öppen pajskiva från centrum av pajdiagrammet uttrycks som procent av pajens diameter. Läs/skriv Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Anger vinkeln för den första paj- eller donutskivan i grader (medurs från upp, 0-360 grader). Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till föräldragruppen. Använd ParentSeriesGroup.FirstSliceAngle för att läsa/skriva och ändra värdet. Skrivskyddad UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Returnerar formatet för en serie. Skrivskyddad [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Returnerar eller anger avståndet, som procent av markörens bredd, mellan dataserier i ett 3D-diagram. Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till föräldragruppen. Använd ParentSeriesGroup.GapDepth för att läsa/skriva och ändra värdet. Skrivskyddad Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Anger avståndet mellan stapel- eller kolumnkluster, som procent av stapel- eller kolumnbredden. Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till föräldragruppen. Använd ParentSeriesGroup.GapWidth för att läsa/skriva och ändra värdet. Skrivskyddad Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Bestämmer om det finns serielinjer för denna serie och liknande serier. Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till föräldragruppen. Använd ParentSeriesGroup.HasSeriesLines för att läsa/skriva och ändra värdet. Använd ParentSeriesGroup.SeriesLinesFormat-egenskapen för att formatera serielinjer. Skrivskyddad Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Bestämmer om linje- eller aktiediagram har upp/ner-staplar. Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till föräldragruppen. Använd ParentSeriesGroup.UpDownBars.HasUpDownBars för att läsa/skriva och ändra värdet. Använd ParentSeriesGroup.UpDownBars-egenskapen för att formatera upp/ner-staplar. Skrivskyddad Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Anger inverterad solid färg för serien. För att tillämpa färginställningen ställ in serieformatets FillType till FillType.Solid. Läs/skriv [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Anger att stapel-, kolumn- eller bubbelsektion ska invertera sina färger om värdet är negativt. Läs/skriv Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Anger att varje datamarkör i serien har en annan färg. Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till föräldragruppen. Använd ParentSeriesGroup.IsColorVaried för att läsa/skriva och ändra värdet. Skrivskyddad Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Returnerar etiketterna för en serie. Skrivskyddad [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Markerare. Skrivskyddad [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Returnerar seriens namn. Skrivskyddad [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Läs/skriv String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Läs/skriv String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Läs/skriv String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Läs/skriv String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Returnerar ordningen för en serie. Läs/skriv Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Anger hur mycket staplar och kolumner överlappar i 2-D-diagram, som procent (från -100 % till 100 %). Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. För att ändra värdet, använd !:ParentSeriesGroup.Overlap-egenskapen för läs/skriv. Skrivskyddad SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Representerar layouten för föräldrakategorietiketter. Gäller endast för Trädkartdiagram. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Skrivskyddad [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Anger hur man bestämmer vilka datapunkter som hamnar i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldragruppen. Använd ParentSeriesGroup.PieSplitBy för att läsa/skriva och ändra värdet. Skrivskyddad [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Den anpassade split-informationen för ett paj-av-paj- eller stapel-av-paj-diagram med anpassad split. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln. Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Skrivskyddad [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Anger ett värde som ska användas för att bestämma vilka datapunkter som hamnar i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Används tillsammans med PieSplitBy-egenskapen. Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldragruppen. Använd ParentSeriesGroup.PieSplitPosition för att läsa/skriva och ändra värdet. Skrivskyddad Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Anger om denna serie plottas på sekundär axel. Läs/skriv Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Representerar kvartilsmetod. Gäller endast för BoxAndWhisker-diagram. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Representerar legendpost relaterad till denna serie. Skrivskyddad [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Anger storleken på den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram, som procent av den första pajens storlek (kan vara mellan 5 och 200 %). Detta är en egenskap som gäller för hela seriegruppen, inte bara för denna serie – en projicering av motsvarande gruppegenskap. Därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldragruppen. Använd ParentSeriesGroup.SecondPieSize för att läsa/skriva och ändra värdet. Skrivskyddad UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Representerar anslutningslinjer. Gäller endast för Waterfall-diagram. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Representerar innerpunkter. Sant om innerpunkter visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Representerar medellinje. Sant om medellinje visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Representerar medelmärkare. Sant om medelmärkare visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Representerar avvikande punkter. Sant om avvikande punkter visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Representerar kurvutjämning. Sant om kurvutjämning är aktiverad för linjediagrammet eller spridningsdiagrammet. Gäller endast för linje- och spridningsdiagram med linjer. Läs/skriv Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Samling av serietrendlinjer. Skrivskyddad [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Returnerar typen för denna serie. Läs/skriv [`ChartType`](../charttype). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Returnerar en automatisk färg för serien baserat på seriens index och diagramstil. Denna färg används som standard om FillType är lika med NotDefined. |

### Se också

* gränssnitt [IChartSeries](../ichartseries)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->