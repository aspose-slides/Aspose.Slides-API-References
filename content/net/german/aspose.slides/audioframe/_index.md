---
title: AudioFrame
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt einen Audioclip auf einer Folie dar.
type: docs
weight: 790
url: /de/aspose.slides/audioframe/
---

## AudioFrame-Klasse

Stellt einen Audioclip auf einer Folie dar.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten der Form zurück. Nur-Lesen [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verbunden ist. Lesen/Schreiben String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der mit einer Form verbunden ist. Lesen/Schreiben String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Gibt den Index der letzten Spur zurück oder legt ihn fest. Lesen/Schreiben Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Gibt die Zeit der letzten Spur zurück oder legt sie fest. Lesen/Schreiben Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Gibt den Startindex der Spur zurück oder legt ihn fest. Lesen/Schreiben Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Gibt die Startzeit der Spur zurück oder legt sie fest. Lesen/Schreiben Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Diese Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus dargestellt wird. Lesen/Schreiben [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Nur-Lesen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lesen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die Pixel-Effekte enthält, die auf eine Form angewendet werden. Hinweis: kann für bestimmte Formtypen, die keine Effekteigenschaften haben, null zurückgeben. Nur-Lesen [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Bestimmt, ob ein Ton in einer Präsentation eingebettet ist. Nur-Lesen Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Gibt das eingebettete Audioobjekt zurück oder legt es fest. Lesen/Schreiben [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. Lesen/Schreiben Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Gibt die Zeitdauer für das ausblenden des Mediums in Millisekunden an. Lesen/Schreiben Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften einer Form enthält. Hinweis: kann für bestimmte Formtypen, die keine Fülleigenschaften haben, null zurückgeben. Nur-Lesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formenrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lesen/Schreiben Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lesen/Schreiben Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Bestimmt, ob ein AudioFrame verborgen ist. Lesen/Schreiben Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den definierten Hyperlink für einen Mausklick zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den definierten Hyperlink für die Mouseover-Aktion zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Bestimmt, ob der PictureFrame ein Cameo-Objekt ist oder nicht. Nur-Lesen Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ markieren' zurück oder legt sie fest. Lesen/Schreiben Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lesen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur-Lesen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften einer Form enthält. Hinweis: kann für bestimmte Formtypen, die keine Linieeigenschaften haben, null zurückgeben. Nur-Lesen [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Gibt den Namen einer Audiodatei zurück oder legt ihn fest, der mit einem AudioFrame verlinkt ist. Lesen/Schreiben String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Muss nicht null sein. Verwenden Sie einen leeren String, falls nötig. Lesen/Schreiben String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt die eindeutige Identifikation der Form im Folienumfang zurück. Nur-Lesen UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) für die eindeutige Identifikation der Form im Präsentationsumfang. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls null. Nur-Lesen [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Gibt das PictureFillFormat-Objekt für einen Bilderrahmen zurück. Nur-Lesen [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesen [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lesen [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Lesen/Schreiben Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Bestimmt, ob ein Audio in einer Schleife abgespielt wird. Lesen/Schreiben Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest. Lesen/Schreiben [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lesen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des rohen Formenrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Gibt die Skalierung der Höhe (relativ zur ursprünglichen Bildgröße) des Bilderrahmens zurück oder legt sie fest. Der Wert 1.0 entspricht 100%. Lesen/Schreiben Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Gibt die Skalierung der Breite (relativ zur ursprünglichen Bildgröße) des Bilderrahmens zurück oder legt sie fest. Der Wert 1.0 entspricht 100%. Lesen/Schreiben Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Bestimmt, ob das Audio nach der Wiedergabe automatisch zurückgespult wird. Lesen/Schreiben Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die z-Achse gedreht ist. Ein positives Wert zeigt eine Drehung im Uhrzeigersinn an; ein negatives Wert eine Drehung gegen den Uhrzeigersinn. Lesen/Schreiben Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesen [`IPictureFrameLock`](../ipictureframelock). (2 Eigenschaften) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Stilobjekt der Form zurück. Nur-Lesen [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Gibt den AutoShape-Typ für einen PictureFrame zurück oder legt ihn fest. Alle Elemente des Sets [`ShapeType`](../shapetype), mit Ausnahme aller Arten von Linien, sind erlaubt: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lesen [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formtypen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur-Lesen [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Gibt die Zeitdauer an, die während der Wiedergabe vom Ende des Mediums entfernt werden soll, in Millisekunden. Lesen/Schreiben Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Gibt die Zeitdauer an, die während der Wiedergabe vom Anfang des Mediums entfernt werden soll, in Millisekunden. Lesen/Schreiben Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt die eindeutige Identifikation der Form im Präsentationsumfang zurück. Nur-Lesen UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) für die eindeutige Identifikation der Form im Folienumfang. |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Gibt die Lautstärke des Audios zurück oder legt sie fest. Lesen/Schreiben [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Gibt die Lautstärke des Audios in Prozent zurück oder legt sie fest. Lesen/Schreiben Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lesen/Schreiben Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/Schreiben Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/Schreiben Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der z-Reihenfolge zurück. Nur-Lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn es keinen gibt, und setzt die Platzhaltereigenschaften auf einen bestimmten Wert. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array der Formelemente zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Ein null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt eine Kopie des Pfades der Geometrieform zurück. Die Koordinaten sind relativ zur oberen linken Ecke der Form. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt die Miniaturansicht der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt die Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Formgeometrie basierend auf dem [`IGeometryPath`](../igeometrypath)-Objekt. Die Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) auf benutzerdefiniert. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Formgeometrie aus einem Array von [`IGeometryPath`](../igeometrypath). Die Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) auf benutzerdefiniert. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Beispiele

Die folgenden Beispiele zeigen, wie die Audio-Wiedergabeoptionen geändert werden.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Holt die AudioFrame-Form
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Setzt den Wiedergabemodus auf Wiedergabe bei Klick
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Setzt die Lautstärke auf niedrig
    audioFrame.Volume = AudioVolumeMode.Low;
    // Setzt den Audio auf die Wiedergabe über Folien hinweg
    audioFrame.PlayAcrossSlides = true;
    // Deaktiviert die Schleife für das Audio
    audioFrame.PlayLoopMode = false;
    // Versteckt den AudioFrame während der Diashow
    audioFrame.HideAtShowing = true;
    // Spult das Audio nach der Wiedergabe zurück
    audioFrame.RewindAudio = true;
    // Speichert die PowerPoint-Datei auf der Festplatte
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Klasse [PictureFrame](../pictureframe)
* Schnittstelle [IAudioFrame](../iaudioframe)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->