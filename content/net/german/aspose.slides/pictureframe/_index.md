---
title: PictureFrame
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt einen Rahmen mit einem Bild darin dar.
type: docs
weight: 9140
url: /de/aspose.slides/pictureframe/
---

## PictureFrame-Klasse

Stellt einen Rahmen mit einem Bild darin dar.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten der Form zurück. Nur lesbar [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den mit einer Form verknüpften Alternativtext zurück oder legt ihn fest. Lese-/Schreib-Zeichenfolge. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des mit einer Form verknüpften Alternativtexts zurück oder legt ihn fest. Lese-/Schreib-Zeichenfolge. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreib [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur lesbar Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: Kann für bestimmte Arten von Formen, die keine Effekteigenschaften haben, null zurückgeben. Nur lesbar [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Füll-Eigenschaften haben, null zurückgeben. Nur lesbar [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmens der Form zurück oder legt sie fest. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreib Einzelwert. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreib Boolescher Wert. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreib [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesbar [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für das Überfahren mit der Maus definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreib [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Bestimmt, ob der PictureFrame ein Cameo-Objekt ist oder nicht. Nur lesbar Boolescher Wert. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder legt die Option 'Als dekorativ markieren' fest. Lese-/Schreib Boolescher Wert. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur lesbar Boolescher Wert. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur lesbar Boolescher Wert. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Linieneigenschaften haben, null zurückgeben. Nur lesbar [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie einen leeren Stringwert, wenn nötig. Lese-/Schreib-Zeichenfolge. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt die eindeutige Form-ID im Folienbereich. Nur lesbar UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) für das Abrufen der eindeutigen Form-ID im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Gibt das PictureFillFormat-Objekt für einen Bilderahmen zurück. Nur lesbar [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Gibt die Sperren der Form zurück. Nur lesbar [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohrahmens der Form zurück oder legt sie fest. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Gibt die Skalierung der Höhe (relativ zur ursprünglichen Bildgröße) des Bilderahmens zurück oder legt sie fest. Ein Wert von 1.0 entspricht 100 %. Lese-/Schreib Einzelwert. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Gibt die Skalierung der Breite (relativ zur ursprünglichen Bildgröße) des Bilderahmens zurück oder legt sie fest. Ein Wert von 1.0 entspricht 100 %. Lese-/Schreib Einzelwert. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die z-Achse rotiert ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreib Einzelwert. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesbar [`IPictureFrameLock`](../ipictureframelock). (2 Eigenschaften) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Stilobjekt der Form zurück. Nur lesbar [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Gibt den AutoShape-Typ für einen PictureFrame zurück oder legt ihn fest. Alle Elemente der Menge [`ShapeType`](../shapetype) sind zulässig, außer aller Arten von Linien: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur lesbar [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur lesbar [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt die eindeutige Form-ID im Präsentationsbereich. Nur lesbar UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) für das Abrufen der eindeutigen Form-ID im Folienbereich. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreib Einzelwert. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreib Einzelwert. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreib Einzelwert. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form ganz hinten in der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form ganz vorne in der z-Reihenfolge zurück. Nur lesbar Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und legt die Eigenschaften des Platzhalters auf einen bestimmten fest. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array von Elementen der Form zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Ein Null-Wert wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt die Kopie des Pfades der Geometrieform zurück. Die Koordinaten sind relativ zur oberen linken Ecke der Form. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](../igeometrypath) Objekt. Die Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) auf Benutzerdefiniert. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Geometrie der Form aus einem Array von [`IGeometryPath`](../igeometrypath). Die Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) auf Benutzerdefiniert. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Beispiele

Die folgenden Beispiele zeigen, wie man das Miniaturbild eines Audio-Frames ändert.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Fügt der Folie einen Audio-Frame an einer bestimmten Position und Größe hinzu.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Fügt ein Bild zu den Präsentationsressourcen hinzu.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Setzt das Bild für den Audio-Frame.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//Speichert die modifizierte Präsentation auf der Festplatte
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Klasse [GeometryShape](../geometryshape)
* Schnittstelle [IPictureFrame](../ipictureframe)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->