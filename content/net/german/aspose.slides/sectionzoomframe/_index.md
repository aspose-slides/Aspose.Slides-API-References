---  
title: SectionZoomFrame
second_title: Aspose.Slides für .NET API-Referenz  
description: Stellt ein Section Zoom-Objekt in einer Folie dar.
type: docs
weight: 9510  
url: /de/aspose.slides/sectionzoomframe/
---  

## SectionZoomFrame-Klasse  

Stellt ein Section Zoom-Objekt in einer Folie dar.  

```csharp  
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame  
```  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzeichenfolge. |  
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzeichenfolge. |  
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreib [`BlackWhiteMode`](../blackwhitemode). |  
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur-lesend Int32. |  
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-lesend [`ICustomData`](../icustomdata). |  
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: Kann null für bestimmte Arten von Formen, die keine Effekteigenschaften haben, zurückgeben. Nur-lesend [`IEffectFormat`](../ieffectformat). |  
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Arten von Formen, die keine Fülleigenschaften haben, zurückgeben. Nur-lesend [`IFillFormat`](../ifillformat). |  
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder setzt sie. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |  
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur-lesend [`IGraphicalObjectLock`](../igraphicalobjectlock). |  
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt sie. Lese-/Schreibeinheit. |  
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreib Boolean. |  
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder setzt ihn. Lese-/Schreib [`IHyperlink`](../ihyperlink). |  
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-lesend [`IHyperlinkManager`](../ihyperlinkmanager). |  
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für die Mauszeigerbewegung definierten Hyperlink zurück oder setzt ihn. Lese-/Schreib [`IHyperlink`](../ihyperlink). |  
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Gibt den Bildtyp eines Zoom-Objekts zurück oder setzt ihn. Lese-/Schreib [`ZoomImageType`](../zoomimagetype). Standardwert: Vorschau |  
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ kennzeichnen' zurück oder setzt sie. Lese-/Schreib Boolean. |  
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-lesend Boolean. |  
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. Nur-lesend Boolean. |  
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Arten von Formen, die keine Linien Eigenschaften haben, zurückgeben. Nur-lesend [`ILineFormat`](../ilineformat). |  
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt ihn. Darf nicht null sein. Verwenden Sie einen leeren Zeichenfolgenwert, falls erforderlich. Lese-/Schreibzeichenfolge. |  
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt die eindeutige Formkennung im Folienbereich zurück. Nur-lesend UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) zum Abrufen der eindeutigen Formkennung im Präsentationsbereich. |  
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-lesend [`IGroupShape`](../igroupshape). |  
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-lesend [`IPlaceholder`](../iplaceholder). |  
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-lesend [`IPresentation`](../ipresentation). |  
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des rohen Formrahmens zurück oder setzt sie. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |  
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Gibt das Navigationsverhalten in der Diashow zurück oder setzt es. Lese-/Schreib Boolean. Standardwert: false |  
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt die, um die die angegebene Form um die z-Achse gedreht wird. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibseinheit. |  
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-lesend [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |  
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Gibt den Wert zurück oder setzt diesen, der angibt, ob das Zoom die Hintergrundfolie des Ziel-Folien verwenden wird. Lese-/Schreib Boolean. Standardwert: true |  
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-lesend [`IBaseSlide`](../ibaseslide). |  
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Gibt das Abschnittsobjekt zurück oder setzt es, auf das das Section Zoom-Objekt verlinkt. Lese-/Schreib [`ISection`](../isection). |  
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt Eigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, zurückgeben. Nur-lesend [`IThreeDFormat`](../ithreedformat). |  
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Gibt die Dauer der Übergangs zwischen Zoom und Folie zurück oder setzt sie. Lese-/Schreibseinheit. Standardwert: 1.0f |  
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt die eindeutige Formkennung im Präsentationsbereich zurück. Nur-lesend UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) zum Abrufen der eindeutigen Formkennung im Folienbereich. |  
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt sie. Lese-/Schreibseinheit. |  
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibseinheit. |  
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibseinheit. |  
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Gibt das Bild für das Zoom-Objekt zurück oder setzt es. Lese-/Schreib [`IPPImage`](../ippimage). |  
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form im hinteren Teil der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form im vorderen Teil der z-Reihenfolge zurück. Nur-lesend Int32. |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn es noch keinen gibt, und setzt die Platzhaltereigenschaften auf einen bestimmten. |  
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder Masterfolie, von der die aktuelle Form abgeleitet ist). Es wird null zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |  
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapeThumbnailBounds.Shape für die Miniaturbildschränke wird standardmäßig verwendet. |  
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |  
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |  
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |  
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |  

### Siehe auch  

* Klasse [ZoomObject](../zoomobject)  
* Schnittstelle [ISectionZoomFrame](../isectionzoomframe)  
* Namespace [Aspose.Slides](../../aspose.slides)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  