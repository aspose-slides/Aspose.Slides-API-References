---
title: Table
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Tabelle auf einer Folie dar.
type: docs
weight: 10880
url: /de/aspose.slides/table/
---
## Table Klasse

Stellt eine Tabelle auf einer Folie dar.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Eigenschaften

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der einer Form zugeordnet ist. Lesen/Schreiben String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der einer Form zugeordnet ist. Lesen/Schreiben String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Gibt an, wie eine Form im Schwarz-weiß-Anzeigemodus dargestellt wird. Lesen/Schreiben [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Gibt die Sammlung von Spalten zurück. Nur lesbar [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungsstellen der Form zurück. Nur lesbar Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen. Nur lesbar [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Gibt ein TableFormat.FillFormat-Objekt zurück, das die Füllformatierung für die Tabelle enthält. Nur lesbar [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Legt fest, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Legt fest, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur lesbar [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Liest oder setzt die Höhe der Form, gemessen in Punkten. Lesen/Schreiben Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Legt fest, ob die Form ausgeblendet ist. Lesen/Schreiben Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Legt fest, ob gerade Zeilen mit einer anderen Formatierung gezeichnet werden sollen. Lesen/Schreiben Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesbar [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Maus-over definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Liest oder setzt die Option 'Als Dekorativ markieren'. Lesen/Schreiben Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Legt fest, ob die Form gruppiert ist. Nur lesbar Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Legt fest, ob die Form TextHolder_PPT ist. Nur lesbar Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Gibt die Zelle an den angegebenen Spalten- und Zeilenindizes zurück. Nur lesbar [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Legt fest, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Legt fest, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linieneigenschaften für eine Form enthält. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine Linieneigenschaften besitzen. Nur lesbar [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Bei Bedarf leere Zeichenkette verwenden. Lesen/Schreiben String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur lesbar UInt32. Siehe auch [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter einer Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Legt fest, ob die Tabelle von rechts nach links gelesen wird. Lesen/Schreiben Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die Z-Achse gedreht wird. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Gegen-Uhrzeigersinn. Lesen/Schreiben Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Gibt die Sammlung von Zeilen zurück. Nur lesbar [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesbar [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur lesbar [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Liest oder setzt den integrierten Tabellenstil. Lesen/Schreiben [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Gibt das TableFormat-Objekt zurück, das Formatierungseigenschaften für diese Tabelle enthält. Nur lesbar [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen. Nur lesbar [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt einen internen, präsenzbezogenen Bezeichner zurück, der für die Verwendung durch Add-Ins oder anderen Code vorgesehen ist. Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als dauerhaft eindeutiger Schlüssel behandelt werden. Nur lesbar UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Legt fest, ob gerade Spalten mit einer anderen Formatierung gezeichnet werden sollen. Lesen/Schreiben Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Liest oder setzt die Breite der Form, gemessen in Punkten. Lesen/Schreiben Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Liest oder setzt die x-Koordinate der oberen linken Ecke der Form, gemessen in Punkten. Lesen/Schreiben Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Liest oder setzt die y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten. Lesen/Schreiben Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form im hinteren Teil der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form im vorderen Teil der Z-Reihenfolge zurück. Nur lesbar Int32. |

## Methoden

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (eine Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form geerbt wird). Gibt null zurück, wenn die aktuelle Form nicht geerbt ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Vorschaubild der Form zurück. Standardmäßig wird der Typ ShapeThumbnailBounds.Shape für die Vorschaubild-Grenzen verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Vorschaubild der Form zurück. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Liest die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Führt benachbarte Zellen zusammen. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Legt fest, dass diese Form kein Platzhalter ist. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Setzt die definierten Absatzformat-Eigenschaften für alle Absätze der Tabellenzellen. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Setzt die definierten Portion-Format-Eigenschaften für alle Portionen der Tabellenzellen. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Setzt die definierten Textfeld-Format-Eigenschaften für alle Textfelder der Tabellenzellen. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../graphicalobject)
* Schnittstelle [ITable](../itable)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->