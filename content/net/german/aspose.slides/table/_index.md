---
title: Tabelle
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Tabelle auf einer Folie dar.
type: docs
weight: 10550
url: /de/aspose.slides/table/
---

## Table-Klasse

Stellt eine Tabelle auf einer Folie dar.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den Alternativtext zurück oder setzt ihn, der mit einer Form verbunden ist. Lese-/Schreib-String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des Alternativtexts zurück oder setzt ihn, der mit einer Form verbunden ist. Lese-/Schreib-String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreib- [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Gibt die Sammlung der Spalten zurück. Nur-Lese [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Nur-Lese Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lese [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die auf eine Form angewendeten Pixeleffekte enthält. Hinweis: kann null für bestimmte Typen von Formen zurückgeben, die keine Effekteigenschaften haben. Nur-Lese [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Gibt ein TableFormat.FillFormat-Objekt zurück, das die Füllformatierung für die Tabelle enthält. Nur-Lese [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Bestimmt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lese-/Schreib-Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Bestimmt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lese-/Schreib-Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmens der Form zurück oder setzt sie. Lese-/Schreib- [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt sie. Lese-/Schreib-Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreib-Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Bestimmt, ob die geraden Zeilen mit einer anderen Formatierung gezeichnet werden müssen. Lese-/Schreib-Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder setzt ihn. Lese-/Schreib- [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lese [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für den Mouseover definierten Hyperlink zurück oder setzt ihn. Lese-/Schreib- [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder setzt die Option 'Als dekorativ markieren'. Lese-/Schreib-Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lese Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur-Lese Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Gibt die Zelle an den angegebenen Spalten- und Zeilenindizes zurück. Nur-Lese [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Bestimmt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lese-/Schreib-Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Bestimmt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lese-/Schreib-Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungs Eigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Typen von Formen zurückgeben, die keine Linieneigenschaften haben. Nur-Lese [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt ihn. Darf nicht null sein. Verwenden Sie einen leeren String, wenn nötig. Lese-/Schreib-String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt die eindeutige Formkennung im Folienkontext. Nur-Lese UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) zum Abrufen der eindeutigen Formkennung im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, falls die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lese [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lese [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lese [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Rahmens der Form zurück oder setzt sie. Lese-/Schreib- [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Bestimmt, ob die Tabelle eine von rechts nach links verlaufende Leseordnung hat. Lese-/Schreib-Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt sie, um die die angegebene Form um die z-Achse rotiert ist. Ein positiver Wert zeigt eine Uhrzeiger-Rotation an; ein negativer Wert zeigt eine gegen den Uhrzeigersinn drehung an. Lese-/Schreib-Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Gibt die Sammlung der Zeilen zurück. Nur-Lese [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lese [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Holt oder setzt den integrierten Tabellenstil. Lese-/Schreib- [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Gibt das TableFormat-Objekt zurück, das die Formatierungseigenschaften für diese Tabelle enthält. Nur-Lese [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Typen von Formen zurückgeben, die keine 3D-Eigenschaften haben. Nur-Lese [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt die eindeutige Formkennung im Präsentationskontext. Nur-Lese UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) zum Abrufen der eindeutigen Formkennung im Folienkontext. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Bestimmt, ob die geraden Spalten mit einer anderen Formatierung gezeichnet werden müssen. Lese-/Schreib-Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt sie. Lese-/Schreib-Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreib-Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreib-Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form im Z-Ordinal zurück. Shapes[0] gibt die Form ganz hinten im Z-Ordinal zurück, und Shapes[Shapes.Count - 1] gibt die Form ganz vorne im Z-Ordinal zurück. Nur-Lese Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn es keinen gibt, und setzt die Platzhaltereigenschaften auf die übergebene. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form von der Layout- und/oder Masterfolie, von der die aktuelle Form abgeleitet ist). Null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Thumbnail der Form zurück. ShapeThumbnailBounds.Shape-Thumbnail-Grenztyp wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Thumbnail der Form zurück. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Merges benachbarte Zellen. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Setzt definierte Absatzeigenschaften für alle Absätze der Tabellenzellen. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Setzt definierte Portionsformate für alle Portionen der Tabellenzellen. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Setzt definierte Textrahmeneigenschaften für alle Textrahmen der Tabellenzellen. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../graphicalobject)
* Schnittstelle [ITable](../itable)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->