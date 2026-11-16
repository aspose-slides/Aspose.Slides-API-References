---
title: IChartSeries
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en diagramserie.
type: docs
weight: 1950
url: /sv/aspose.slides.charts/ichartseries/
---
## IChartSeries gränssnitt

Representerar en diagramserie.

```csharp
public interface IChartSeries : IChartComponent
```

## Egenskaper

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Tillåter att hämta bas IChartComponent gränssnittet. Skrivskyddad [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Anger formen för en serie i ett 3-D-stapeldiagram. Ändring av värdet för denna egenskap kan leda till att typ av serie ändras automatiskt. Läs/skriv [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Anger hur bubbelstorleksvärdena representeras i bubbel-diagrammet. Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.BubbleSizeRepresentation läs/skriv egenskap för att ändra värdet. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Anger skalningsfaktorn för bubbel-diagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.BubbleSizeScale läs/skriv egenskap för att ändra värdet. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Returnerar samling av datapunkter för denna serie. Skrivskyddad [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Anger storleken på hålet i ett doughnut-diagram (kan vara mellan 10 och 90 procent av plot-areans storlek). Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.DoughnutHoleSize läs/skriv egenskap för att ändra värdet. Skrivskyddad Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Representerar ErrorBars för en serie med riktning X. ErrorBars med X-riktning är tillgängliga för serier av typen area, bar, scatter och bubble. För andra diagramtyper returnerar egenskapen null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samlingen för att specificera värdet (med [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)-egenskapen). Skrivskyddad [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Representerar ErrorBars för en serie med riktning Y. ErrorBars med Y-riktning är tillgängliga för serier av typen area, bar, line, scatter och bubble. För andra diagramtyper returnerar egenskapen null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samlingen för att specificera värdet (med [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)-egenskapen). Skrivskyddad [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Avståndet för en öppen tårtbit från mitten av tårtdiagrammet uttrycks som procent av tårtans diameter. Läs/skriv Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Anger vinkeln för den första tårt- eller doughnut-biten, i grader (medurs från toppen, 0 till 360 grader). Denna egenskap är skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.FirstSliceAngle läs/skriv egenskap för att ändra värdet. Skrivskyddad UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Returnerar formatet för en serie. Skrivskyddad [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Returnerar eller anger avståndet, som procent av markörens bredd, mellan dataserier i ett 3D-diagram. Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.GapDepth läs/skriv egenskap för att ändra värdet. Skrivskyddad Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Anger avståndet mellan stapel- eller kolumnkluster, som procent av stapel- eller kolumnbredden. Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.GapWidth läs/skriv egenskap för att ändra värdet. Skrivskyddad Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Bestämmer huruvida serien har serielinjer och besläktade serier. Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.HasSeriesLines läs/skriv egenskap för att ändra värdet. Använd ParentSeriesGroup.SeriesLinesFormat-egenskapen för att formatera serielinjer. Skrivskyddad Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Bestämmer huruvida linje- eller stapeldiagram har upp/ner-staplar. Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.UpDownBars.HasUpDownBars läs/skriv egenskap för att ändra värdet. Använd ParentSeriesGroup.UpDownBars-egenskapen för att formatera upp/ner-staplar. Skrivskyddad Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Anger inverterad solid färg för serien. För att tillämpa färginställningen sätt serieformatets FillType till FillType.Solid. Läs/skriv [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Anger att stapel-, kolumn- eller bubbelseriens färger ska inverteras om värdet är negativt. Läs/skriv Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Anger att varje datamarkör i serien har en annan färg. Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.IsColorVaried läs/skriv egenskap för att ändra värdet. Skrivskyddad Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Returnerar etiketterna för en serie. Skrivskyddad [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Returnerar serie-markör. Skrivskyddad [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Returnerar serienamn. Skrivskyddad [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Returnerar eller anger talformatet för serie-bubbelsstorlekar. Läs/skriv String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Returnerar eller anger talformatet för serievärden. Läs/skriv String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Returnerar eller anger talformatet för serie-x-värden. Läs/skriv String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Returnerar eller anger talformatet för serie-y-värden. Läs/skriv String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Returnerar ordningen för en serie. Läs/skriv Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Anger hur mycket staplar och kolumner överlappar i 2-D-diagram, i procent (från -100 % till 100 %). Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap och är därför skrivskyddad. För att ändra värdet, använd ParentSeriesGroup.Overlap läs/skriv egenskap. Skrivskyddad SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Representerar layout av föräldrakategorimärkningar. Gäller endast för Treemap-diagram. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Returnerar föräldraseriegruppen. Skrivskyddad [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Anger hur man bestämmer vilka datapunkter som ska ligga i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.PieSplitBy läs/skriv egenskap för att ändra värdet. Skrivskyddad [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Den anpassade split-informationen för ett pie-of-pie- eller bar-of-pie-diagram med anpassad split. Innehåller datapunkter som ska ritas i den andra tårtan eller stapeln. Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Skrivskyddad [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Anger ett värde som ska användas för att bestämma vilka datapunkter som ligger i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med PieSplitBy-egenskapen. Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.PieSplitPosition läs/skriv egenskap för att ändra värdet. Skrivskyddad Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Anger om denna serie plottas på sekundär värdeaxel. Läs/skriv Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Representerar kvartilsmetod. Gäller endast för BoxAndWhisker-diagram. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Representerar legend-post relaterad till denna serie. Skrivskyddad [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Anger storleken på den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som procent av den första tårtans storlek (kan vara mellan 5 och 200 procent). Denna egenskap gäller inte bara för denna serie utan för alla serier i den överordnade seriegruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegruppen. Använd ParentSeriesGroup.SecondPieSize läs/skriv egenskap för att ändra värdet. Skrivskyddad UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Representerar anslutningslinjer. Gäller endast för Waterfall-diagram. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Representerar inre punkter. True om inre punkter visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Representerar medelvärdesmärken. True om medellinje visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Representerar medelvärdesmärken. True om medelvärdesmärken visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Representerar avvikande punkter. True om avvikande punkter visas i BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Representerar kurvutjämning. True om kurvutjämning är påslagen för linje- eller spridningsdiagram som är kopplade med linjer. Gäller endast för linje- och spridningsdiagram med linjekoppling. Läs/skriv Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Samling av serietrendlinjer. Skrivskyddad [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Returnerar en typ för denna serie. Läs/skriv [`ChartType`](../charttype). |

## Metoder

| Name | Description |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Returnerar en automatisk färg för serien baserat på serie-index och diagramstil. Denna färg används som standard om FillType är lika med NotDefined. |

### Se även

* gränssnitt [IChartComponent](../ichartcomponent)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->