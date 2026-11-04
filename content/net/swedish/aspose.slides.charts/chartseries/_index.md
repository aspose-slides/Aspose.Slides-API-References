---
title: ChartSeries
second_title: Aspose.Slides för .NET API-referens
description: Representerar en diagramserie.
type: docs
weight: 1450
url: /sv/aspose.slides.charts/chartseries/
---
## ChartSeries klass

Representerar en diagramserie.

```csharp
public class ChartSeries : IChartSeries
```

## Egenskaper

| Name | Description |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Anger formen för en serie i ett 3-D stapeldiagram. Ändring av värdet för denna egenskap kan leda till automatisk förändring av serietyp. Läs/skriv [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Anger hur bubbelstorleksvärdena representeras i bubbeldiagrammet. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.BubbleSizeRepresentation-egenskap för att läsa/skriva värdet. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Anger skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 % av standardstorleken). Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.BubbleSizeScale-egenskap för att läsa/skriva värdet. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Returnerar det överordnade diagrammet. Skrivskyddad [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Returnerar samling av datapunkter för denna serie. Skrivskyddad [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Anger storleken på hålet i ett munkdiagram (kan vara mellan 10 och 90 % av plot-ytans storlek). Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.DoughnutHoleSize-egenskap för att läsa/skriva värdet. Skrivskyddad Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Representerar ErrorBars för serie med riktning X. ErrorBars med X-riktning är tillgängliga för serier av typ area, bar, scatter och bubble. För alla andra diagramtyper returnerar egenskapen null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samling för att ange värde (med [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)-egenskap). Skrivskyddad [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Representerar ErrorBars för serie med riktning Y. ErrorBars med Y-riktning är tillgängliga för serier av typ area, bar, line, scatter och bubble. För alla andra diagramtyper returnerar egenskapen null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samling för att ange värde (med [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)-egenskap). Skrivskyddad [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Avståndet för en öppen tårtbit från centrum av tårtdiagrammet anges som procent av tårtdiametern. Läs/skriv Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Anger vinkeln för den första tårta- eller munkbiten i grader (medurs från toppen, 0 till 360 grader). Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.FirstSliceAngle-egenskap för att läsa/skriva värdet. Skrivskyddad UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Returnerar formatet för en serie. Skrivskyddad [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Returnerar eller sätter avståndet, som procent av markörens bredd, mellan dataserier i ett 3D-diagram. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.GapDepth-egenskap för att läsa/skriva värdet. Skrivskyddad Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Anger avståndet mellan stapel- eller kolumnkluster, som procent av stapel- eller kolumnbredden. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.GapWidth-egenskap för att läsa/skriva värdet. Skrivskyddad Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Avgör om det finns serielinjer för denna serie och närliggande serier. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.HasSeriesLines-egenskap för att läsa/skriva värdet. Använd ParentSeriesGroup.SeriesLinesFormat-egenskap för att formatera serielinjer. Skrivskyddad Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Avgör om ett linje- eller stapeldiagram har upp-/ned-staplar. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.UpDownBars.HasUpDownBars-egenskap för att läsa/skriva värdet. Använd ParentSeriesGroup.UpDownBars-egenskap för att formatera upp-/ned-staplar. Skrivskyddad Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Anger inverterad solid färg för serien. För att tillämpa färginställning, sätt serieformatets FillType till FillType.Solid. Läs/skriv [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Anger att stapel-, kolumn- eller bubbelsekvensen ska invertera sina färger om värdet är negativt. Läs/skriv Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Anger att varje datamarkör i serien har en annan färg. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.IsColorVaried-egenskap för att läsa/skriva värdet. Skrivskyddad Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Returnerar etiketterna för en serie. Skrivskyddad [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Markör. Skrivskyddad [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Returnerar seriens namn. Skrivskyddad [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Läs/skriv String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Läs/skriv String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Läs/skriv String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Läs/skriv String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Returnerar ordningen för en serie. Läs/skriv Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Anger hur mycket staplar och kolumner överlappar på 2-D-diagram, som procent (från -100 % till 100 %). Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd !:ParentSeriesGroup.Overlap-egenskap för att läsa/skriva värdet. Skrivskyddad SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Representerar layout för överordnade kategorietiketter. Gäller endast för Treemap-diagram. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Skrivskyddad [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Anger hur man bestämmer vilka datapunkter som ingår i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.PieSplitBy-egenskap för att läsa/skriva värdet. Skrivskyddad [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Den anpassade split-informationen för ett pie-of-pie- eller bar-of-pie-diagram med anpassad split. Innehåller datapunkter som ska ritas i den andra tårtan eller stapeln. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Skrivskyddad [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Anger ett värde som ska användas för att bestämma vilka datapunkter som ingår i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med PieSplitBy-egenskapen. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.PieSplitPosition-egenskap för att läsa/skriva värdet. Skrivskyddad Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Anger om denna serie är renderad på sekundär axel. Läs/skriv Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Representerar kvartilsmetod. Gäller endast för BoxAndWhisker-diagram. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Representerar legendpost kopplad till denna serie. Skrivskyddad [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Anger storleken på den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som procent av den första tårtans storlek (kan vara mellan 5 och 200 %). Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – den är en projicering av lämplig gruppegenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.SecondPieSize-egenskap för att läsa/skriva värdet. Skrivskyddad UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Representerar anslutningslinjer. Gäller endast för Waterfall-diagram. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Representerar inre punkter. Sant om inre punkter visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Representerar medelvärdeslinje. Sant om medelvärdeslinje visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Representerar medelvärdesmarkörer. Sant om medelvärdesmarkörer visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Representerar avvikande punkter. Sant om avvikande punkter visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Representerar kurvutjämning. Sant om kurvutjämning är påslagen för linjediagram eller spridningsdiagram. Gäller endast för linje- och spridningsdiagram som är sammankopplade med linjer. Läs/skriv Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Samling av seriers trendlinjer. Skrivskyddad [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Returnerar typen för denna serie. Läs/skriv [`ChartType`](../charttype). |

## Metoder

| Name | Description |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Returnerar en automatisk färg för serien baserat på serie-index och diagramstil. Denna färg används som standard om FillType är NotDefined. |

### Se även

* gränssnitt [IChartSeries](../ichartseries)
* namnrum [Aspose.Slides.Charts](../../aspose.slides.charts)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->