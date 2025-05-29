---
title: AudioFrame
second_title: Aspose.Slides für .NET API Referenz
description: Stellt einen Audioausschnitt auf einer Folie dar.
type: docs
weight: 790
url: /de/aspose.slides/audioframe/
---

## AudioFrame-Klasse

Stellt einen Audioausschnitt auf einer Folie dar.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten der Form zurück. Nur Lesezugriff [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Texts zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Gibt den Index der letzten Spur zurück oder setzt ihn. Lese-/Schreibzugriff Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Gibt die Zeit der letzten Spur zurück oder setzt sie. Lese-/Schreibzugriff Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Gibt den Index der Startspur zurück oder setzt ihn. Lese-/Schreibzugriff Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Gibt die Zeit der Startspur zurück oder setzt sie. Lese-/Schreibzugriff Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft bestimmt, wie eine Form im Schwarz-Weiß-Anzeigemodus dargestellt wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur Lesezugriff Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur Lesezugriff [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: kann für bestimmte Arten von Formen, die keine Effekt-Eigenschaften haben, null zurückgeben. Nur Lesezugriff [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Bestimmt, ob ein Klang in eine Präsentation eingebettet ist. Nur Lesezugriff Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Gibt das eingebettete Audioobjekt zurück oder setzt es. Lese-/Schreibzugriff [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Gibt die Zeitdauer für das anfängliche Überblenden des Mediums in Millisekunden an. Lese-/Schreibzugriff Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Gibt die Zeitdauer für das abschließende Überblenden des Mediums in Millisekunden an. Lese-/Schreibzugriff Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Arten von Formen, die keine Füll-Eigenschaften haben, null zurückgeben. Nur Lesezugriff [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften der Formrahmen zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Bestimmt, ob ein AudioFrame verborgen ist. Lese-/Schreibzugriff Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für einen Mausklick definierten Hyperlink zurück oder setzt ihn. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur Lesezugriff [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder setzt ihn. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Bestimmt, ob der PictureFrame ein Cameo-Objekt ist oder nicht. Nur Lesezugriff Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder setzt die Option „Als dekorativ markieren“. Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur Lesezugriff Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur Lesezugriff Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Arten von Formen, die keine Linien-Eigenschaften haben, null zurückgeben. Nur Lesezugriff [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Gibt den Namen einer Audiodatei zurück oder setzt ihn, die mit einem AudioFrame verknüpft ist. Lese-/Schreibzugriff String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt ihn. Darf nicht null sein. Verwenden Sie leere Zeichenfolgenwerte, wenn nötig. Lese-/Schreibzugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt die eindeutige Formenkennung im Folienkontext. Nur Lesezugriff UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) zum Abrufen der eindeutigen Formenkennung im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur Lesezugriff [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Gibt das PictureFillFormat-Objekt für einen Bilderahmen zurück. Nur Lesezugriff [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur Lesezugriff [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Lese-/Schreibzugriff Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Bestimmt, ob ein Audio in Schleife abgespielt wird. Lese-/Schreibzugriff Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Gibt den Audio-Wiedergabemodus zurück oder setzt ihn. Lese-/Schreibzugriff [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur Lesezugriff [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des rohen Formrahmens zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Gibt die Skalierung der Höhe (relativ zur originalen Bildgröße) des Bilderahmens zurück oder setzt sie. Wert 1.0 entspricht 100%. Lese-/Schreibzugriff Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Gibt die Skalierung der Breite (relativ zur originalen Bildgröße) des Bilderahmens zurück oder setzt sie. Wert 1.0 entspricht 100%. Lese-/Schreibzugriff Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Bestimmt, ob Audio nach der Wiedergabe automatisch zum Anfang zurückgespult wird. Lese-/Schreibzugriff Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt sie, um die die angegebene Form um die z-Achse gedreht wird. Ein positiver Wert deutet auf eine Drehung im Uhrzeigersinn hin; ein negativer Wert steht für eine Drehung gegen den Uhrzeigersinn. Lese-/Schreibzugriff Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IPictureFrameLock`](../ipictureframelock). (2 Eigenschaften) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Stilobjekt der Form zurück. Nur Lesezugriff [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Gibt den AutoShape-Typ für einen PictureFrame zurück oder setzt ihn. Es sind alle Elemente der Menge [`ShapeType`](../shapetype) zulässig, außer alle Arten von Linien: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur Lesezugriff [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: kann für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur Lesezugriff [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Gibt die Zeitdauer an, die während der Wiedergabe vom Ende des Mediums entfernt werden soll, in Millisekunden. Lese-/Schreibzugriff Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Gibt die Zeitdauer an, die während der Wiedergabe vom Anfang des Mediums entfernt werden soll, in Millisekunden. Lese-/Schreibzugriff Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt die eindeutige Formenkennung im Präsentationskontext. Nur Lesezugriff UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) zum Abrufen der eindeutigen Formenkennung im Folienkontext. |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Gibt die Lautstärke des Audios zurück oder setzt sie. Lese-/Schreibzugriff [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Gibt die Lautstärke des Audios in Prozent zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der Z-Reihenfolge zurück. Nur Lesezugriff Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf eine angegebene. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array der Formelemente zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt die Kopie des Pfades der Geometrieform zurück. Die Koordinaten sind relativ zur linken oberen Ecke der Form. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Geometrie der Form von einem [`IGeometryPath`](../igeometrypath)-Objekt. Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) in Benutzerdefiniert. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Geometrie der Form von einem Array von [`IGeometryPath`](../igeometrypath). Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) in Benutzerdefiniert. |
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
    // Setzt das Audio auf Wiedergabe über Folien hinweg
    audioFrame.PlayAcrossSlides = true;
    // Deaktiviert die Schleife für das Audio
    audioFrame.PlayLoopMode = false;
    // Versteckt den AudioFrame während der Diashow
    audioFrame.HideAtShowing = true;
    // Spult das Audio nach der Wiedergabe automatisch zum Start zurück
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