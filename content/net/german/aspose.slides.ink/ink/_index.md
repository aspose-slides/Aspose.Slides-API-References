---
title: Ink
second_title: Aspose.Slides für .NET API Referenz
description: Stellt ein Tintenobjekt auf einer Folie dar.
type: docs
weight: 7320
url: /de/aspose.slides.ink/ink/
---

## Tinte-Klasse

Stellt ein Tintenobjekt auf einer Folie dar.

```csharp
public class Ink : GraphicalObject, IInk
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Texts zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus dargestellt wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Nur Lesezugriff Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur Lesezugriff [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Hinweis: kann für bestimmte Typen von Formen null zurückgeben, die keine Effekteigenschaften haben. Nur Lesezugriff [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen null zurückgeben, die keine Fülleigenschaften haben. Nur Lesezugriff [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmens der Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für einen Mausklick definierten Hyperlink zurück oder setzt ihn. Lese-/Schreibzugriff [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur Lesezugriff [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für die Mausbewegung definierten Hyperlink zurück oder setzt ihn. Lese-/Schreibzugriff [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ruft die Option 'Als dekorativ markieren' ab oder setzt sie. Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur Lesezugriff Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur Lesezugriff Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen null zurückgeben, die keine Linienspezifiken haben. Nur Lesezugriff [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt ihn. Darf nicht null sein. Verwenden Sie im Bedarfsfall einen leeren String. Lese-/Schreibzugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ruft die eindeutige Identifikationsnummer der Form im Folienkontext ab. Nur Lesezugriff UInt32. Siehe auch [`UniqueId`](../../aspose.slides/shape/uniqueid) um die eindeutige Identifikationsnummer der Form im Präsentationskontext zu erhalten. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls gibt null zurück. Nur Lesezugriff [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur Lesezugriff [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur Lesezugriff [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des rohen Rahmens der Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt sie, um die die angegebene Form um die z-Achse rotiert ist. Ein positiver Wert bedeutet eine Drehung im Uhrzeigersinn; ein negativer Wert bedeutet eine Drehung gegen den Uhrzeigersinn. Lese-/Schreibzugriff Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur Lesezugriff [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen null zurückgeben, die keine 3D-Eigenschaften haben. Nur Lesezugriff [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | Ruft alle Spuren ab, die im IInk-Element [`IInkTrace`](../iinktrace) enthalten sind. Nur Lesezugriff. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ruft die eindeutige ID der Form im Präsentationskontext ab. Nur Lesezugriff UInt32. Siehe auch [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) um die eindeutige Identifikationsnummer der Form im Folienkontext zu erhalten. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form im Z-Ordnung zurück. Shapes[0] gibt die Form an der Rückseite der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form an der Vorderseite der Z-Reihenfolge zurück. Nur Lesezugriff Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls noch kein Platzhalter vorhanden ist, und setzt die Platzhaltereigenschaften auf eine bestimmte. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine Grundform des Platzhalters zurück (Form von der Layout- und/oder Masterfolie, von der die aktuelle Form abgeleitet ist). Eine null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../../aspose.slides/graphicalobject)
* Schnittstelle [IInk](../iink)
* Namespace [Aspose.Slides.Ink](../../aspose.slides.ink)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->