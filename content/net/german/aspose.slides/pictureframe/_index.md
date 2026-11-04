---
title: PictureFrame
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt einen Rahmen mit einem Bild darin dar.
type: docs
weight: 9430
url: /de/aspose.slides/pictureframe/
---
## PictureFrame Klasse

Stellt einen Rahmen mit einem Bild darin dar.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten der Form zurück. Nur-Lesen [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der einer Form zugeordnet ist. Lesen/Schreiben String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der einer Form zugeordnet ist. Lesen/Schreiben String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Legt fest, wie eine Form im Schwarz-Weiß-Anzeige-Modus gerendert wird. Lesen/Schreiben [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte der Form zurück. Nur-Lesen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lesen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte einer Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen, null zurückgeben. Nur-Lesen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformat-Eigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen, null zurückgeben. Nur-Lesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form in Punkt zurück oder legt sie fest. Lesen/Schreiben Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lesen/Schreiben Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den Hyperlink zurück oder legt ihn fest, der für einen Mausklick definiert ist. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den Hyperlink zurück oder legt ihn fest, der für das Mouse-Over definiert ist. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Bestimmt, ob das PictureFrame ein Cameo-Objekt ist oder nicht. Nur-Lesen Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option „Als dekorativ markieren“ zurück oder legt sie fest. Lesen/Schreiben Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lesen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur-Lesen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformat-Eigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine Linien-Eigenschaften besitzen, null zurückgeben. Nur-Lesen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Lesen/Schreiben String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und es PowerPoint oder Interop-Code ermöglicht, die Form von überall im Dokument zuverlässig zu referenzieren. Nur-Lesen UInt32. Siehe auch [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls null. Nur-Lesen [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Gibt das PictureFillFormat-Objekt für einen Bildrahmen zurück. Nur-Lesen [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesen [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lesen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lesen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Gibt den Skalierungsfaktor der Höhe (relativ zur Originalbildgröße) des Bildrahmens zurück oder legt ihn fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Gibt den Skalierungsfaktor der Breite (relativ zur Originalbildgröße) des Bildrahmens zurück oder legt ihn fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen/Schreiben Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesen [`IPictureFrameLock`](../ipictureframelock). (2 Eigenschaften) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Style-Objekt der Form zurück. Nur-Lesen [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Gibt den AutoShape-Typ für ein PictureFrame zurück oder legt ihn fest. Alle Elemente des Satzes [`ShapeType`](../shapetype) sind zulässig, außer allen Arten von Linien: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lesen [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen, null zurückgeben. Nur-Lesen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code bestimmt ist. Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel verwendet werden. Nur-Lesen UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form in Punkt zurück oder legt sie fest. Lesen/Schreiben Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die X-Koordinate der oberen linken Ecke der Form in Punkt zurück oder legt sie fest. Lesen/Schreiben Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die Y-Koordinate der oberen linken Ecke der Form in Punkt zurück oder legt sie fest. Lesen/Schreiben Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] liefert die Form ganz hinten, Shapes[Shapes.Count - 1] die Form ganz vorne. Nur-Lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array der Form-Elemente zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine Basis-Platzhalter-Form zurück (Form aus dem Layout- und/oder Master-Slide, von dem die aktuelle Form ererbt wird). Gibt null zurück, wenn die aktuelle Form nicht ererbt ist. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt die Kopie des Pfads der Geometrie-Form zurück. Koordinaten sind relativ zur linken oberen Ecke der Form. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapeThumbnailBounds.Shape für Miniaturbildgrenzen wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Liefert die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Formgeometrie aus dem [`IGeometryPath`](../igeometrypath)-Objekt. Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Formtyp ([`ShapeType`](../geometryshape/shapetype)) zu Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Formgeometrie aus einem Array von [`IGeometryPath`](../igeometrypath). Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Formtyp ([`ShapeType`](../geometryshape/shapetype)) zu Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Beispiele

Das folgende Beispiel zeigt, wie das Miniaturbild eines Audio-Frames geändert wird.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Fügt einen Audio-Frame zur Folie mit einer angegebenen Position und Größe hinzu.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Fügt ein Bild zu den Präsentationsressourcen hinzu.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Setzt das Bild für den Audio-Frame.
	//Speichert die geänderte Präsentation auf dem Datenträger
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* class [GeometryShape](../geometryshape)
* interface [IPictureFrame](../ipictureframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->