---
title: SummaryZoomSection
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert ein Summary Zoom SectionObjekt in einem Summary Zoom Frame.
type: docs
weight: 10030
url: /de/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection class

Repräsentiert ein Summary Zoom Section-Objekt in einem Summary Zoom Frame.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den einer Form zugeordneten alternativen Text zurück oder legt ihn fest. Lesen/SchreibenString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück, der einer Form zugeordnet ist, oder legt ihn fest. Lesen/SchreibenString . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | -Eigenschaft gibt an, wie eine Form im Schwarzweiß-Anzeigemodus gerendert wird.. Lesen/Schreiben[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungsstellen in der Form zurück. SchreibgeschütztInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Schreibgeschützt[`ICustomData`](../icustomdata) . |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Gibt die Textbeschreibung des Summary Zoom Section-Objekts zurück. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet wurden. Hinweis: Kann für bestimmte Arten von Formen, die keine Effekteigenschaften haben, null zurückgeben. Schreibgeschützt[`IEffectFormat`](../ieffectformat) . |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Fülleigenschaften haben, null zurückgeben. Schreibgeschützt[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben[`IShapeFrame`](../ishapeframe) . |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschützt[`IGraphicalObjectLock`](../igraphicalobjectlock) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lesen/SchreibenBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Schreibgeschützt[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben[`IHyperlink`](../ihyperlink) . |
| [Image](../../aspose.slides/zoomobject/image) { get; set; } | Holt oder setzt Bild für Zoom-Objekt. Lesen/Schreiben[`IPPImage`](../ippimage) . |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Holt oder setzt den Bildtyp eines Zoom-Objekts. Lesen/Schreiben[`ZoomImageType`](../zoomimagetype) . Standardwert: Vorschau |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. SchreibgeschütztBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. SchreibgeschütztBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Linieneigenschaften haben, null zurückgeben. Schreibgeschützt[`ILineFormat`](../ilineformat) . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert. Lesen/SchreibenString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ruft eine eindeutige Formkennung im Folienbereich ab. SchreibgeschütztUInt32 . Siehe auch[`UniqueId`](../shape/uniqueid) zum Abrufen einer eindeutigen Formkennung im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Schreibgeschützt[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Schreibgeschützt[`IPlaceholder`](../iplaceholder) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Schreibgeschützt[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohformrahmens zurück oder legt sie fest. Lesen/Schreiben[`IShapeFrame`](../ishapeframe) . |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Ruft das Navigationsverhalten in der Diashow ab oder legt es fest. Lesen/SchreibenBoolean . Standardwert: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Gradzahl zurück, um die die angegebene Form um die z-Achse gedreht wird, oder legt sie fest. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lesen/SchreibenSingle . |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschützt[`IGraphicalObjectLock`](../igraphicalobjectlock) . (2 properties) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Erhält oder legt einen Wert fest, der angibt, ob der Zoom den Hintergrund der Zielfolie verwendet. Lesen/SchreibenBoolean . Standardwert: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Schreibgeschützt[`IBaseSlide`](../ibaseslide) . |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Ruft das Abschnittsobjekt ab oder legt es fest, mit dem das Abschnittszoomobjekt verknüpft ist. Lesen/Schreiben[`ISection`](../isection) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form hat. Hinweis: Kann für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Schreibgeschützt[`IThreeDFormat`](../ithreedformat) . |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Gibt den Texttitel des Summary Zoom Section-Objekts zurück. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Ruft die Dauer des Übergangs zwischen Zoom und Folie ab oder legt sie fest. Lesen/SchreibenSingle . Standardwert: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ruft eine eindeutige Formkennung im Darstellungsbereich ab. SchreibgeschütztUInt32 . Siehe auch[`OfficeInteropShapeId`](../shape/officeinteropshapeid) zum Abrufen einer eindeutigen Formkennung im Folienbereich. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form am Ende der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form am Anfang der Z-Reihenfolge zurück. order. SchreibgeschütztInt32 . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf einen angegebenen. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Gibt Form-Miniaturansicht zurück. ShapeThumbnailBounds.Shape Form-Miniatur-Umgrenzungstyp wird standardmäßig verwendet. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Gibt Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt von Shape als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt von Shape als SVG-Datei. |

### Siehe auch

* class [SectionZoomFrame](../sectionzoomframe)
* interface [ISummaryZoomSection](../isummaryzoomsection)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
