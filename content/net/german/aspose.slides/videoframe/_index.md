---
title: VideoFrame
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt einen Videoclip auf einer Folie dar.
type: docs
weight: 10970
url: /de/aspose.slides/videoframe/
---
## VideoFrame class

Stellt einen Videoclip auf einer Folie dar.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten der Form zurück. Schreibgeschützt[`IAdjustValueCollection`](../iadjustvaluecollection) . |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den einer Form zugeordneten alternativen Text zurück oder legt ihn fest. Lesen/SchreibenString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück, der einer Form zugeordnet ist, oder legt ihn fest. Lesen/SchreibenString . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | -Eigenschaft gibt an, wie eine Form im Schwarzweiß-Anzeigemodus gerendert wird.. Lesen/Schreiben[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungsstellen in der Form zurück. SchreibgeschütztInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Schreibgeschützt[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet wurden. Hinweis: Kann für bestimmte Arten von Formen, die keine Effekteigenschaften haben, null zurückgeben. Schreibgeschützt[`IEffectFormat`](../ieffectformat) . |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Gibt das eingebettete Videoobjekt zurück oder legt es fest. Lesen/Schreiben[`IVideo`](../ivideo) . |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Fülleigenschaften haben, null zurückgeben. Schreibgeschützt[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben[`IShapeFrame`](../ishapeframe) . |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Legt fest, ob ein Video im Vollbildmodus angezeigt wird. Lesen/SchreibenBoolean . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lesen/SchreibenBoolean . |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Bestimmt, ob ein VideoFrame ausgeblendet ist. Lesen/SchreibenBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Schreibgeschützt[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. SchreibgeschütztBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. SchreibgeschütztBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Linieneigenschaften haben, null zurückgeben. Schreibgeschützt[`ILineFormat`](../ilineformat) . |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Gibt den Namen einer Videodatei zurück, die mit einem VideoFrame verknüpft ist, oder legt ihn fest. Lesen/SchreibenString . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert. Lesen/SchreibenString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ruft eine eindeutige Formkennung im Folienbereich ab. SchreibgeschütztUInt32 . Siehe auch[`UniqueId`](../shape/uniqueid) zum Abrufen einer eindeutigen Formkennung im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Schreibgeschützt[`IGroupShape`](../igroupshape) . |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Gibt das PictureFillFormat-Objekt für einen Bilderrahmen zurück. Schreibgeschützt[`IPictureFillFormat`](../ipicturefillformat) . |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschützt[`IPictureFrameLock`](../ipictureframelock) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Schreibgeschützt[`IPlaceholder`](../iplaceholder) . |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Bestimmt, ob ein Video geloopt wird. Lesen/SchreibenBoolean . |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Gibt den Video-Wiedergabemodus zurück oder legt ihn fest. Lesen/Schreiben[`VideoPlayModePreset`](../videoplaymodepreset) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Schreibgeschützt[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohformrahmens zurück oder legt sie fest. Lesen/Schreiben[`IShapeFrame`](../ishapeframe) . |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Gibt den Höhenmaßstab (relativ zur ursprünglichen Bildgröße) des Bilderrahmens zurück oder legt ihn fest. Wert 1,0 entspricht 100 %. Lesen/SchreibenSingle . |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Gibt den Breitenmaßstab (relativ zur ursprünglichen Bildgröße) des Bildrahmens zurück oder legt ihn fest. Wert 1,0 entspricht 100 %. Lesen/SchreibenSingle . |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Legt fest, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film beendet ist. Lesen/SchreibenBoolean . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Gradzahl zurück, um die die angegebene Form um die z-Achse gedreht wird, oder legt sie fest. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lesen/SchreibenSingle . |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschützt[`IPictureFrameLock`](../ipictureframelock) . (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Stilobjekt der Form zurück. Schreibgeschützt[`IShapeStyle`](../ishapestyle) . |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Gibt den AutoForm-Typ für einen PictureFrame zurück oder setzt ihn. Es sind alle Elemente des Satzes zulässig[`ShapeType`](../shapetype), außer allen möglichen Zeilen: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Schreibgeschützt[`IBaseSlide`](../ibaseslide) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form hat. Hinweis: Kann für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Schreibgeschützt[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ruft eine eindeutige Formkennung im Darstellungsbereich ab. SchreibgeschütztUInt32 . Siehe auch[`OfficeInteropShapeId`](../shape/officeinteropshapeid) zum Abrufen einer eindeutigen Formkennung im Folienbereich. |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Gibt die Audiolautstärke zurück oder stellt sie ein. Lesen/Schreiben[`AudioVolumeMode`](../audiovolumemode) . |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form am Ende der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form am Anfang der Z-Reihenfolge zurück. order. SchreibgeschütztInt32 . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf einen angegebenen. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt ein Array von Formelementen und gibt es zurück. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt die Kopie des Pfads der Geometrieform zurück. Koordinaten sind relativ zur linken oberen Ecke der Form. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Gibt Form-Miniaturansicht zurück. ShapeThumbnailBounds.Shape Form-Miniatur-Umgrenzungstyp wird standardmäßig verwendet. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Gibt Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert Formgeometrie von[`IGeometryPath`](../igeometrypath) Objekt. Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype) ) zuCustom . |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Formgeometrie aus einem Array von[`IGeometryPath`](../igeometrypath). Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype) ) zuCustom . |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt von Shape als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt von Shape als SVG-Datei. |

### Siehe auch

* class [PictureFrame](../pictureframe)
* interface [IVideoFrame](../ivideoframe)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
