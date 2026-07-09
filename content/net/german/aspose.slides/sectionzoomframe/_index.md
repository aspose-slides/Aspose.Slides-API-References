---
title: SectionZoomFrame
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt ein Section-Zoom-Objekt in einer Folie dar.
type: docs
weight: 9780
url: /de/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame Klasse

Stellt ein Section-Zoom-Objekt in einer Folie dar.

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lesen/Schreiben String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lesen/Schreiben String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeigemodus dargestellt wird. Lesen/Schreiben [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Anschlusspunkte der Form zurück. Nur gelesen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur gelesen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: Kann für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen, null zurückgeben. Nur gelesen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen, null zurückgeben. Nur gelesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur gelesen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lesen/Schreiben Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für einen Mausklick definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur gelesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Maus-Überfahren definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Gibt den Bildtyp eines Zoom-Objekts zurück oder legt ihn fest. Lesen/Schreiben [`ZoomImageType`](../zoomimagetype). Standardwert: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ markieren' zurück oder legt sie fest. Lesen/Schreiben Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur gelesen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur gelesen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine Linien-Eigenschaften besitzen, null zurückgeben. Nur gelesen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert. Lesen/Schreiben String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig aus jeder Stelle des Dokuments zu referenzieren. Nur gelesen UInt32. Siehe auch [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur gelesen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter einer Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur gelesen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur gelesen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Gibt das Navigationsverhalten in der Bildschirmpraesentation zurück oder legt es fest. Lesen/Schreiben Boolean. Standardwert: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen/Schreiben Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur gelesen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Gibt den Wert zurück oder legt ihn fest, der angibt, ob der Zoom den Hintergrund der Ziel-Folien verwendet. Lesen/Schreiben Boolean. Standardwert: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur gelesen [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Gibt das Abschnitts-Objekt zurück oder legt es fest, auf das das SectionZoom-Objekt verweist. Lesen/Schreiben [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen, null zurückgeben. Nur gelesen [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Gibt die Dauer des Übergangs zwischen Zoom und Folie zurück oder legt sie fest. Lesen/Schreiben Single. Standardwert: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt einen internen, präsenta tionsbezogenen Bezeichner zurück, der für die Verwendung durch Add-Ins oder anderen Code gedacht ist. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden. Nur gelesen UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Gibt das Bild für das Zoom-Objekt zurück oder legt es fest. Lesen/Schreiben [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form zurück, die hinten in der Z-Reihenfolge liegt, und Shapes[Shapes.Count - 1] gibt die Form zurück, die vorne liegt. Nur gelesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine einfache Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form ererbt wird). Null wird zurückgegeben, wenn die aktuelle Form nicht ererbt wird. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Vorschaubild der Form zurück. ShapeThumbnailBounds.Shape wird standardmäßig als Typ für Formen-Thumbnail-Grenzen verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Vorschaubild der Form zurück. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Gibt die visuellen Grenzen der Form zurück, berechnet aus ihrem gerenderten Inhalt. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [ZoomObject](../zoomobject)
* Schnittstelle [ISectionZoomFrame](../isectionzoomframe)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->