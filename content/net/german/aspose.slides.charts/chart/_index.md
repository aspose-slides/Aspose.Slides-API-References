---
title: Chart
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt ein grafisches Diagramm auf einer Folie dar.
type: docs
weight: 1140
url: /de/aspose.slides.charts/chart/
---
## Chart class

Stellt ein grafisches Diagramm auf einer Folie dar.

```csharp
public class Chart : GraphicalObject, IChart
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den einer Form zugeordneten alternativen Text zurück oder legt ihn fest. Lesen/SchreibenString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück, der einer Form zugeordnet ist, oder legt ihn fest. Lesen/SchreibenString . |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Ermöglicht das Abrufen der Basis-IFormattedTextContainer-Schnittstelle. Schreibgeschützt[`IFormattedTextContainer`](../iformattedtextcontainer) . |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Ermöglicht das Abrufen der IThemeable-Basisschnittstelle. Schreibgeschützt[`IThemeable`](../../aspose.slides.theme/ithemeable) . |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Bietet Zugriff auf Diagrammachsen. Schreibgeschützt[`IAxesManager`](../iaxesmanager) . |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Gibt ein Objekt zurück, das es ermöglicht, das Format der Rückwand eines 3D-Diagramms zu ändern. Schreibgeschützt[`IChartWall`](../ichartwall) . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | -Eigenschaft gibt an, wie eine Form im Schwarzweiß-Anzeigemodus gerendert wird.. Lesen/Schreiben[`BlackWhiteMode`](../../aspose.slides/blackwhitemode) . |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Gibt Informationen über die verknüpften oder eingebetteten Daten zurück, die einem Diagramm zugeordnet sind. Schreibgeschützt[`IChartData`](../ichartdata) . |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Gibt eine Datentabelle eines Diagramms zurück. Schreibgeschützt[`IDataTable`](../idatatable) . |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Gibt einen Diagrammtitel zurück oder legt ihn fest. Schreibgeschützt[`IChartTitle`](../icharttitle) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungsstellen in der Form zurück. SchreibgeschütztInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Schreibgeschützt[`ICustomData`](../../aspose.slides/icustomdata) . |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Gibt zurück oder legt fest, wie leere Zellen in einem Diagramm dargestellt werden. Lesen/Schreiben[`DisplayBlanksAsType`](../displayblanksastype) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet wurden. Hinweis: Kann für bestimmte Arten von Formen, die keine Effekteigenschaften haben, null zurückgeben. Schreibgeschützt[`IEffectFormat`](../../aspose.slides/ieffectformat) . |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Fülleigenschaften haben, null zurückgeben. Schreibgeschützt[`IFillFormat`](../../aspose.slides/ifillformat) . |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Gibt ein Objekt zurück, das es ermöglicht, das Format des Bodens eines 3D-Diagramms zu ändern. Schreibgeschützt[`IChartWall`](../ichartwall) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben[`IShapeFrame`](../../aspose.slides/ishapeframe) . |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschützt[`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock) . |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Bestimmt, ob ein Diagramm eine Datentabelle hat. Lesen/SchreibenBoolean . |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Bestimmt, ob ein Diagramm eine Legende hat. Lesen/SchreibenBoolean . |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/SchreibenBoolean . |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lesen/SchreibenBoolean . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lesen/SchreibenBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben[`IHyperlink`](../../aspose.slides/ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Schreibgeschützt[`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben[`IHyperlink`](../../aspose.slides/ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. SchreibgeschütztBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. SchreibgeschütztBoolean . |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Gibt eine Legende für ein Diagramm zurück oder legt sie fest. Schreibgeschützt[`ILegend`](../ilegend) . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Linieneigenschaften haben, null zurückgeben. Schreibgeschützt[`ILineFormat`](../../aspose.slides/ilineformat) . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert. Lesen/SchreibenString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ruft eine eindeutige Formkennung im Folienbereich ab. SchreibgeschütztUInt32 . Siehe auch[`UniqueId`](../../aspose.slides/shape/uniqueid) zum Abrufen einer eindeutigen Formkennung im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Schreibgeschützt[`IGroupShape`](../../aspose.slides/igroupshape) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Schreibgeschützt[`IPlaceholder`](../../aspose.slides/iplaceholder) . |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Repräsentiert den Plotbereich eines Diagramms. Schreibgeschützt[`IChartPlotArea`](../ichartplotarea) . |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Legt fest, ob nur die sichtbaren Zellen gezeichnet werden. False, um sowohl sichtbare als auch verborgene Zellen zu zeichnen. Lesen/SchreibenBoolean . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Schreibgeschützt[`IPresentation`](../../aspose.slides/ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohformrahmens zurück oder legt sie fest. Lesen/Schreiben[`IShapeFrame`](../../aspose.slides/ishapeframe) . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Gradzahl zurück, um die die angegebene Form um die z-Achse gedreht wird, oder legt sie fest. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lesen/SchreibenSingle . |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Gibt eine 3D-Rotation eines Diagramms zurück. Schreibgeschützt[`IRotation3D`](../irotation3d) . |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschützt[`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock) . (2 properties) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lesen/SchreibenBoolean . |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Gibt ein Objekt zurück, das es ermöglicht, das Format der Seitenwand eines 3D-Diagramms zu ändern. Schreibgeschützt[`IChartWall`](../ichartwall) . |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Schreibgeschützt[`IBaseSlide`](../../aspose.slides/ibaseslide) . |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Gibt den Diagrammstil zurück oder legt ihn fest. Lesen/Schreiben[`StyleType`](../styletype) . |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Gibt das Textformat des Diagramms zurück. Die Eigenschaft gilt nicht für die folgenden Typen:Treemap ,Sunburst , Waterfall ,Histogram ,Funnel,BoxAndWhisker . Schreibgeschützt[`IChartTextFormat`](../icharttextformat) . |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Gibt den Themenmanager zurück. Schreibgeschützt[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form hat. Hinweis: Kann für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Schreibgeschützt[`IThreeDFormat`](../../aspose.slides/ithreedformat) . |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Gibt den Diagrammtyp zurück oder legt ihn fest. Lesen/Schreiben[`ChartType`](../charttype) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ruft eine eindeutige Formkennung im Darstellungsbereich ab. SchreibgeschütztUInt32 . Siehe auch[`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) zum Abrufen einer eindeutigen Formkennung im Folienbereich. |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Geben Sie die oben auf dem Diagramm gezeichneten Formen an. Schreibgeschützt[`IGroupShape`](../../aspose.slides/igroupshape) . |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form am Ende der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form am Anfang der Z-Reihenfolge zurück. order. SchreibgeschütztInt32 . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf einen angegebenen. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Gibt ein effektives Thema für dieses Diagramm zurück. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Gibt Form-Miniaturansicht zurück. ShapeThumbnailBounds.Shape Form-Miniatur-Umgrenzungstyp wird standardmäßig verwendet. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Gibt Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Berechnet tatsächliche Werte von Diagrammelementen. Die tatsächlichen Werte umfassen die Position von Elementen, die die IActualLayout-Schnittstelle (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und tatsächliche Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.Actual.Actual , IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt von Shape als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt von Shape als SVG-Datei. |

### Siehe auch

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IChart](../ichart)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
