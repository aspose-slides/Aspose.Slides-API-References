---
title: Chart
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett grafiskt diagram på en bild.
type: docs
weight: 1240
url: /sv/aspose.slides.charts/chart/
---
## Chart klass

Representerar ett grafiskt diagram på en bild.

```csharp
public class Chart : GraphicalObject, IChart
```

## Egenskaper

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln på den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Tillåter att hämta bas-gränssnittet IFormattedTextContainer. Endast läs [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Tillåter att hämta bas-gränssnittet IThemeable. Endast läs [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Tillhandahåller åtkomst till diagramaxlar. Endast läs [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Returnerar ett objekt som möjliggör att ändra formatet på bakväggen i ett 3D-diagram. Endast läs [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen anger hur en form ska renderas i svart-vit visningsläge. Läs/skriv [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Returnerar information om den länkade eller inbäddade data som är associerad med ett diagram. Endast läs [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Returnerar en data-tabell för ett diagram. Endast läs [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Returnerar eller anger en diagramrubrik. Endast läs [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på formen. Endast läs Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Endast läs [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Returnerar eller anger hur tomma celler ska plottas i ett diagram. Läs/skriv [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form. Observera: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Endast läs [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformaterings-egenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har fyllnings-egenskaper. Endast läs [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Returnerar ett objekt som möjliggör att ändra formatet på golvet i ett 3D-diagram. Endast läs [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger formramens egenskaper. Läs/skriv [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Returnerar formens lås. Endast läs [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Avgör om ett diagram har en data-tabell. Läs/skriv Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Avgör om ett diagram har en legend. Läs/skriv Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Anger att diagramområdet ska ha rundade hörn. Läs/skriv Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Avgör om ett diagram har en synlig rubrik. Läs/skriv Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger formens höjd, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Avgör om formen är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänks-hanteraren. Endast läs [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för muspekare. Läs/skriv [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Avgör om formen är grupperad. Endast läs Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Avgör om formen är TextHolder_PPT. Endast läs Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Returnerar eller anger en legend för ett diagram. Endast läs [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformaterings-egenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har linje-egenskaper. Endast läs [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Får inte vara null. Använd tom sträng om så behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en bild-specifik unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från vilken plats som helst i dokumentet. Endast läs UInt32. Se även [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras null. Endast läs [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Endast läs [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Representerar diagrammets plot-område. Endast läs [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Avgör om endast synliga celler plottas. False för att plotta både synliga och dolda celler. Läs/skriv Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Endast läs [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger den råa formramens egenskaper. Läs/skriv [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna formen roteras runt z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Returnerar en 3D-rotation för ett diagram. Endast läs [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Returnerar formens lås. Endast läs [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 egenskaper) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Anger att datalabels över diagrammets maximum ska visas. Läs/skriv Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Returnerar ett objekt som möjliggör att ändra formatet på sidoväggen i ett 3D-diagram. Endast läs [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en form. Endast läs [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Returnerar eller anger diagramstilen. Läs/skriv [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Returnerar diagramtextformat. Egenskapen gäller inte för följande typer: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Endast läs [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Returnerar temahanteraren. Endast läs [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet med 3D-effektegenskaper för en form. Observera: kan returnera null för vissa typer av former som saknar 3D-egenskaper. Endast läs [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Returnerar eller anger diagramtypen. Läs/skriv [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentation-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte betraktas som en bestående unik nyckel. Endast läs UInt32. Se även [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Anger formerna som ritas ovanpå diagrammet. Endast läs [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger formens bredd, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en form i z-ordning. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Endast läs Int32. |

## Metoder

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållaregenskaper till en angiven. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Returnerar ett effektivt tema för detta diagram. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från). Returnerar null om den aktuella formen inte ärvs. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar formens miniatyr. Standard är ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyr. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar formens visuella gränser beräknade från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna form inte är en platshållare. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Beräknar faktiska värden för diagramdelar. De faktiska värdena inkluderar positioner för element som implementerar IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) samt faktiska axelvärden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar innehållet i Shape som en SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar innehållet i Shape som en SVG-fil. |

### Se även

* klass [GraphicalObject](../../aspose.slides/graphicalobject)
* gränssnitt [IChart](../ichart)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->