---  
title: LegacyDiagram
second_title: Aspose.Sildes für .NET API Referenz  
description: Stellt ein Legacy-Diagrammobjekt dar.
type: docs  
weight: 7430  
url: /de/aspose.slides/legacydiagram/
---  

## LegacyDiagram-Klasse  

Stellt ein Legacy-Diagrammobjekt dar.  

```csharp  
public class LegacyDiagram : GraphicalObject, ILegacyDiagram  
```  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |  
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |  
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | Ermöglicht den Zugriff auf die Basis-IGraphicalObject-Schnittstelle. Nur Lesezugriff [`IGraphicalObject`](../igraphicalobject). |  
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Diese Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../blackwhitemode). |  
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Nur Lesezugriff Int32. |  
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur Lesezugriff [`ICustomData`](../icustomdata). |  
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die auf eine Form angewendeten Pixeleffekte enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Effekteigenschaften haben, null zurückgeben. Nur Lesezugriff [`IEffectFormat`](../ieffectformat). |  
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Fülleigenschaften haben, null zurückgeben. Nur Lesezugriff [`IFillFormat`](../ifillformat). |  
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmen der Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |  
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IGraphicalObjectLock`](../igraphicalobjectlock). |  
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |  
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff Boolean. |  
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder setzt ihn. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |  
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur Lesezugriff [`IHyperlinkManager`](../ihyperlinkmanager). |  
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder setzt ihn. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |  
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Greift auf die Option "Als dekorativ markieren" zu oder setzt sie. Lese-/Schreibzugriff Boolean. |  
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur Lesezugriff Boolean. |  
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur Lesezugriff Boolean. |  
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Lineareigenschaften haben, null zurückgeben. Nur Lesezugriff [`ILineFormat`](../ilineformat). |  
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt ihn. Darf nicht null sein. Verwenden Sie einen leeren String, falls erforderlich. Lese-/Schreibzugriff String. |  
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt die eindeutige Form-ID im Kontext der Folie zurück. Nur Lesezugriff UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) zum Abrufen der eindeutigen Form-ID im Kontext der Präsentation. |  
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Ansonsten wird null zurückgegeben. Nur Lesezugriff [`IGroupShape`](../igroupshape). |  
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur Lesezugriff [`IPlaceholder`](../iplaceholder). |  
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur Lesezugriff [`IPresentation`](../ipresentation). |  
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohrahmens der Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |  
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt sie, um die die angegebene Form um die z-Achse gedreht ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibzugriff Single. |  
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |  
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur Lesezugriff [`IBaseSlide`](../ibaseslide). |  
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur Lesezugriff [`IThreeDFormat`](../ithreedformat). |  
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt die eindeutige Form-ID im Kontext der Präsentation zurück. Nur Lesezugriff UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) zum Abrufen der eindeutigen Form-ID im Kontext der Folie. |  
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |  
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |  
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |  
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form im hinteren Teil der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form im vorderen Teil der z-Reihenfolge zurück. Nur Lesezugriff Int32. |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhalt Eigenschaften auf einen bestimmten Wert. |  
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | Konvertiert das Legacy-Diagramm in ein bearbeitbares Gruppendiagramm. Das erstellte GroupShape-Objekt wird an der gleichen Position in die übergeordnete Gruppengestalt eingefügt. |  
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | Konvertiert das Legacy-Diagramm in ein bearbeitbares SmartArt-Objekt. Das erstellte SmartArt-Objekt wird an der gleichen Position in die übergeordnete Gruppengestalt eingefügt. |  
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt einen grundlegenden Platzhalter zurück (eine Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Ein null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |  
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt die Miniaturansicht der Form zurück. Der ShapeThumbnailBounds.Shape-Miniaturansichtstyp wird standardmäßig verwendet. |  
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt die Miniaturansicht der Form zurück. |  
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form keinen Platzhalter bildet. |  
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |  
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |  

### Siehe auch  

* Klasse [GraphicalObject](../graphicalobject)  
* Schnittstelle [ILegacyDiagram](../ilegacydiagram)  
* Namensraum [Aspose.Slides](../../aspose.slides)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  