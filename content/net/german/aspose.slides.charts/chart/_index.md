---
title: Chart
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt ein grafisches Diagramm auf einer Folie dar.
type: docs
weight: 1180
url: /de/aspose.slides.charts/chart/
---

## Chart-Klasse

Stellt ein grafisches Diagramm auf einer Folie dar.

```csharp
public class Chart : GraphicalObject, IChart
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Ermöglicht den Zugriff auf die Basis-IFormattedTextContainer-Schnittstelle. Nur Lesezugriff [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Ermöglicht den Zugriff auf die Basis-IThemeable-Schnittstelle. Nur Lesezugriff [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Bietet Zugriff auf die Diagrammaksen. Nur Lesezugriff [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Gibt ein Objekt zurück, mit dem das Format der Rückwand eines 3D-Diagramms geändert werden kann. Nur Lesezugriff [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Gibt Informationen über die mit einem Diagramm verknüpften oder eingebetteten Daten zurück. Nur Lesezugriff [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Gibt eine Datentabelle eines Diagramms zurück. Nur Lesezugriff [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Gibt einen Diagrammtitel zurück oder legt ihn fest. Nur Lesezugriff [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur Lesezugriff Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur Lesezugriff [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Gibt zurück oder legt fest, wie leere Zellen in einem Diagramm gezeichnet werden. Lese-/Schreibzugriff [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die an eine Form angefügten Pixel-Effekte enthält. Hinweis: Kann null für bestimmte Typen von Formen zurückgeben, die keine Effekt-Eigenschaften haben. Nur Lesezugriff [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Typen von Formen zurückgeben, die keine Füll-Eigenschaften haben. Nur Lesezugriff [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Gibt ein Objekt zurück, mit dem das Format des Bodens eines 3D-Diagramms geändert werden kann. Nur Lesezugriff [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmen der Form zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Bestimmt, ob ein Diagramm eine Datentabelle hat. Lese-/Schreibzugriff Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Bestimmt, ob ein Diagramm eine Legende hat. Lese-/Schreibzugriff Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Gibt an, ob der Diagrammbereich abgerundete Ecken haben soll. Lese-/Schreibzugriff Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lese-/Schreibzugriff Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur Lesezugriff [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für den Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder setzt die Option "Als dekorativ markieren". Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur Lesezugriff Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form als TextHolder_PPT dient. Nur Lesezugriff Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Gibt eine Legende für ein Diagramm zurück oder legt sie fest. Nur Lesezugriff [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Typen von Formen zurückgeben, die keine Linien-Eigenschaften haben. Nur Lesezugriff [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Lese-/Schreibzugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt die eindeutige Form-ID im Folienbereich. Nur Lesezugriff UInt32. Siehe auch [`UniqueId`](../../aspose.slides/shape/uniqueid) für den Abruf der eindeutigen Form-ID im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur Lesezugriff [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur Lesezugriff [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Stellt den Plotbereich eines Diagramms dar. Nur Lesezugriff [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Bestimmt, ob nur sichtbare Zellen gezeichnet werden. False, um sowohl sichtbare als auch versteckte Zellen zu zeichnen. Lese-/Schreibzugriff Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur Lesezugriff [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Rohdaten des Rahmen der Form zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert gibt eine Uhrzeigerdrehung an; ein negativer Wert gibt eine gegen den Uhrzeigersinn drehung an. Lese-/Schreibzugriff Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Gibt eine 3D-Drehung eines Diagramms zurück. Nur Lesezugriff [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 Eigenschaften) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Gibt an, ob die Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lese-/Schreibzugriff Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Gibt ein Objekt zurück, mit dem das Format der Seitenwand eines 3D-Diagramms geändert werden kann. Nur Lesezugriff [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur Lesezugriff [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Gibt den Diagrammstil zurück oder legt ihn fest. Lese-/Schreibzugriff [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Gibt das Textformat von Diagrammen zurück. Die Eigenschaft ist nicht anwendbar für folgende Typen: Treemap, Sunburst, Wasserfall, Histogramm, Trichter, BoxAndWhisker. Nur Lesezugriff [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Gibt den Themenmanager zurück. Nur Lesezugriff [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Typen von Formen zurückgeben, die keine 3D-Eigenschaften haben. Nur Lesezugriff [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Gibt den Diagrammtyp zurück oder legt ihn fest. Lese-/Schreibzugriff [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt die eindeutige Form-ID im Präsentationsbereich. Nur Lesezugriff UInt32. Siehe auch [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) für den Abruf der eindeutigen Form-ID im Folienbereich. |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Gibt die Formen an, die über dem Diagramm gezeichnet werden. Nur Lesezugriff [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der Z-Reihenfolge zurück. Nur Lesezugriff Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn es keinen gibt, und setzt die Eigenschaften des Platzhalters auf einen bestimmten. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Gibt ein effektives Thema für dieses Diagramm zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Es wird null zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt die Miniaturansicht der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt die Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Berechnet die aktuellen Werte der Diagrammelemente. Die aktuellen Werte umfassen die Position der Elemente, die die IActualLayout-Schnittstelle implementieren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und aktuelle Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../../aspose.slides/graphicalobject)
* Schnittstelle [IChart](../ichart)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->