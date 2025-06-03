---
title: Chart
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt ein grafisches Diagramm in einer Folie dar.
type: docs
weight: 1180
url: /de/aspose.slides.charts/chart/
---

## Diagramm-Klasse

Stellt ein grafisches Diagramm in einer Folie dar.

```csharp
public class Chart : GraphicalObject, IChart
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Ermöglicht den Zugriff auf die Basisschnittstelle IFormattedTextContainer. Nur-Lese [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Ermöglicht den Zugriff auf die Basisschnittstelle IThemeable. Nur-Lese [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Bietet Zugriff auf die Diagrammachsen. Nur-Lese [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Gibt ein Objekt zurück, das die Formatierung der Rückwand eines 3D-Diagramms ändert. Nur-Lese [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Gibt Informationen über die verknüpften oder eingebetteten Daten zurück, die mit einem Diagramm verknüpft sind. Nur-Lese [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Gibt eine Datentabelle eines Diagramms zurück. Nur-Lese [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Gibt den Titel eines Diagramms zurück oder setzt ihn. Nur-Lese [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Nur-Lese Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lese [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Gibt an, wie leere Zellen in einem Diagramm dargestellt werden sollen. Lese-/Schreibzugriff [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: kann für bestimmte Typen von Formen, die keine Effekt-Eigenschaften haben, null zurückgeben. Nur-Lese [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine Füll-Eigenschaften haben, null zurückgeben. Nur-Lese [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Gibt ein Objekt zurück, das die Formatierung des Bodens eines 3D-Diagramms ändert. Nur-Lese [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmens der Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Bestimmt, ob ein Diagramm eine Datentabelle hat. Lese-/Schreibzugriff Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Bestimmt, ob ein Diagramm eine Legende hat. Lese-/Schreibzugriff Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lese-/Schreibzugriff Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lese-/Schreibzugriff Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder setzt ihn. Lese-/Schreibzugriff [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lese [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für mouse over definierten Hyperlink zurück oder setzt ihn. Lese-/Schreibzugriff [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt den 'Als dekorativ markieren'-Option zurück oder setzt ihn. Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lese Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur-Lese Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Gibt eine Legende für ein Diagramm zurück oder setzt sie. Nur-Lese [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine Linien-Eigenschaften haben, null zurückgeben. Nur-Lese [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt ihn. Darf nicht null sein. Verwenden Sie einen leeren String, wenn erforderlich. Lese-/Schreibzugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt die eindeutige Form-ID im Folienbereich zurück. Nur-Lese UInt32. Siehe auch [`UniqueId`](../../aspose.slides/shape/uniqueid) für das Abrufen der eindeutigen Form-ID im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lese [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lese [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Stellt den Plotbereich eines Diagramms dar. Nur-Lese [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Bestimmt, ob nur die sichtbaren Zellen geplottet werden. False, um sowohl sichtbare als auch verborgene Zellen zu plotten. Lese-/Schreibzugriff Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lese [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des rohen Rahmen einer Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt sie, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibzugriff Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Gibt eine 3D-Drehung eines Diagramms zurück. Nur-Lese [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 Eigenschaften) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lese-/Schreibzugriff Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Gibt ein Objekt zurück, das die Formatierung der Seitenwand eines 3D-Diagramms ändert. Nur-Lese [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lese [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Gibt den Diagrammstil zurück oder setzt ihn. Lese-/Schreibzugriff [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Gibt das Textformat des Diagramms zurück. Die Eigenschaft ist für folgende Typen nicht anwendbar: Treemap, Sunburst, Wasserfall, Histogramm, Trichter, BoxAndWhisker. Nur-Lese [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Gibt den Themenmanager zurück. Nur-Lese [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur-Lese [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Gibt den Diagrammtyp zurück oder setzt ihn. Lese-/Schreibzugriff [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt die eindeutige Form-ID im Präsentationsbereich zurück. Nur-Lese UInt32. Siehe auch [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) für das Abrufen der eindeutigen Form-ID im Folienbereich. |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Gibt die Formen an, die über dem Diagramm gezeichnet werden. Nur-Lese [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der Z-Reihenfolge zurück. Nur-Lese Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf einen bestimmten Wert. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Gibt ein effektives Thema für dieses Diagramm zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form erbt). Eine null wird zurückgegeben, wenn die aktuelle Form nicht erbt. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt die Miniaturansicht der Form zurück. ShapeThumbnailBounds.Shape-Form-Miniaturansicht wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt die Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Berechnet die tatsächlichen Werte der Diagrammelemente. Die tatsächlichen Werte umfassen die Position der Elemente, die das IActualLayout-Interface implementieren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und die tatsächlichen Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../../aspose.slides/graphicalobject)
* Schnittstelle [IChart](../ichart)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->