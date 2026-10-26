---
title: IAudioFrame
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Audioclip auf einer Folie dar.
type: docs
weight: 1353
url: /de/aspose.slides/iaudioframe/
---
## IAudioFrame Klasse

Stellt einen Audioclip auf einer Folie dar.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Erstellt und gibt ein Array von shape-Elementen zurück. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Gibt den Anpassungswert einer Form am angegebenen Index zurück. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Gibt eine Sammlung von shape-Anpassungswerten zurück. Nur lesbar [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Gibt den Alternativtext zurück, der einer Form zugeordnet ist. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Gibt den Titel des Alternativtexts zurück, der einer Form zugeordnet ist. Lesen [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | Gibt den Index der letzten Spur zurück. Lesen **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | Gibt die Zeit der letzten Spur zurück. Lesen **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | Gibt den Index der Startspur zurück. Lesen **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | Gibt die Zeit der Startspur zurück. Lesen **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Eigenschaft legt fest, wie eine Form im Schwarz-weiß-Anzeigemodus gerendert wird. Lesen [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | Gibt die Sammlung geschlossener Untertitel zurück, die dem Audio-Frame zugeordnet sind. Diese Eigenschaft ist schreibgeschützt und liefert ein [ICaptionsCollection](../icaptionscollection/) mit allen Untertitelspuren. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Gibt die Anzahl der Verbindungsstellen der Form zurück. Nur lesbar **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesbar [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Gibt das [EffectFormat](../effectformat/)-Objekt zurück, das Pixeleffekte einer Form enthält. Nur lesbar [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | Bestimmt, ob ein Ton in die Präsentation eingebettet ist. Nur lesbar **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | Gibt das eingebettete Audio-Objekt zurück. Lesen [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. Lesen **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. Lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Gibt das [FillFormat](../fillformat/)-Objekt zurück, das Füllformatierungs-Eigenschaften einer Form enthält. Nur lesbar [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Gibt die Eigenschaften des Formrahmens zurück. Lesen [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Liefert die Höhe der Form in Punkt. Lesen **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Bestimmt, ob die Form ausgeblendet ist. Lesen **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | Bestimmt, ob ein [AudioFrame](../audioframe/) ausgeblendet ist. Lesen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Gibt den für Mausklick definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlink-Verwalter Nur lesbar [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Gibt den für Maus-over definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Gibt die Option „Als dekorativ markieren“ zurück. Lesen/Schreiben **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Bestimmt, ob die Form gruppiert ist. Nur lesbar **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Bestimmt, ob die Form ein TextHolder ist. Nur lesbar **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Gibt das [LineFormat](../lineformat/)-Objekt zurück, das Linienformatierungs-Eigenschaften einer Form enthält. Nur lesbar [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Gibt den Namen einer Audiodatei zurück, die mit einem [AudioFrame](../audioframe/) verknüpft ist. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Gibt den Namen einer Form zurück. Lesen [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der während der Lebensdauer der Form konstant bleibt und es PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur lesbar **uint32_t**. Siehe auch [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Gibt das übergeordnete [GroupShape](../groupshape/)-Objekt zurück, falls die Form gruppiert ist. Andernfalls null. Nur lesbar [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | Gibt das [PictureFillFormat](../picturefillformat/)-Objekt für einen Bildrahmen zurück. Nur lesbar [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | Gibt die Sperren von [PictureFrame](../pictureframe/) zurück. Nur lesbar [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Gibt den Platzhalter für eine Form zurück. Nur lesbar [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Lesen **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | Bestimmt, ob Audio wiederholt wird. Lesen **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | Gibt den Audio-Wiedergabemodus zurück. Lesen [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Gibt die Präsentation zurück. Nur lesbar [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Gibt die rohen Eigenschaften des Formrahmens zurück. Lesen [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | Gibt den Höhen-Skalierungsfaktor (relativ zur ursprünglichen Bildgröße) des Bildrahmens zurück. Der Wert 1,0 entspricht 100 %. Lesen **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | Gibt den Breiten-Skalierungsfaktor (relativ zur ursprünglichen Bildgröße) des Bildrahmens zurück. Der Wert 1,0 entspricht 100 %. Lesen **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | Bestimmt, ob ein Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Lesen **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Gibt die Drehung der angegebenen Form um die Z-Achse in Grad zurück. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Gegen-Uhrzeigersinn. Lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Gibt die Sperren der Form zurück. Nur lesbar [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Gibt das Stil-Objekt der Form zurück. Nur lesbar [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Gibt den Geometrie-Voreinstellungstyp zurück. Hinweis: Beim Ändern des Wertes werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lesen [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Gibt die Basis-Folie zurück. Nur lesbar [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Gibt das [ThreeDFormat](../threedformat/)-Objekt zurück, das Linienformatierungs-Eigenschaften einer Form enthält. Nur lesbar [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt wird, in Millisekunden. Lesen **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | Gibt die Zeitdauer an, die am Anfang des Mediums während der Wiedergabe entfernt wird, in Millisekunden. Lesen **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Gibt eine interne, präsentationsbezogene Kennung zurück, die für Add-Ins oder anderen Code vorgesehen ist. Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel verwendet werden. Nur lesbar **uint32_t**. Siehe auch [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | Gibt die Audio-Lautstärke zurück. Lesen [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | Gibt die Audio-Lautstärke in Prozent zurück. Lesen **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Liefert die Breite der Form in Punkt. Lesen **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Liefert die X-Koordinate der oberen linken Ecke der Form in Punkt. Lesen **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Liefert die Y-Koordinate der oberen linken Ecke der Form in Punkt. Lesen **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] liefert die Form ganz hinten, Shapes[Shapes.Count-1] liefert die Form ganz vorne. Nur lesbar **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout- oder Master-Slide, von dem die aktuelle Form erbt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Gibt eine Kopie des Pfades der Geometrie-Form zurück. Koordinaten sind relativ zur linken oberen Ecke der Form. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Gegenstück zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Gibt das Form-Miniaturbild zurück. Der Standard-Typ für Miniatur-Bounds ist [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Gibt das Form-Miniaturbild zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Gegenstück zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Gegenstück zum C#-Operator „is“. |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-lock()-Statement zum Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Gegenstück zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definiert, dass diese Form kein Platzhalter ist. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Setzt den Alternativtext, der einer Form zugeordnet ist. Schreiben [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Setzt den Titel des Alternativtexts, der einer Form zugeordnet ist. Schreiben [System::String](../../system/string/). |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | Setzt den Index der letzten Spur. Schreiben **int32_t**. |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | Setzt die Zeit der letzten Spur. Schreiben **int32_t**. |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | Setzt den Index der Startspur. Schreiben **int32_t**. |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | Setzt die Zeit der Startspur. Schreiben **int32_t**. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Eigenschaft legt fest, wie eine Form im Schwarz-weiß-Anzeigemodus gerendert wird. Schreiben [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Setzt das eingebettete Audio-Objekt. Schreiben [IAudio](../iaudio/). |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. Schreiben **float**. |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. Schreiben **float**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Setzt die Eigenschaften des Formrahmens. Schreiben [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Setzt die Höhe der Form in Punkt. Schreiben **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Bestimmt, ob die Form ausgeblendet ist. Schreiben **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | Bestimmt, ob ein [AudioFrame](../audioframe/) ausgeblendet ist. Schreiben **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Setzt den für Mausklick definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Setzt den für Maus-over definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Setzt die Option „Als dekorativ markieren“ Lesen/Schreiben **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Setzt den Namen einer Audiodatei, die mit einem [AudioFrame](../audioframe/) verknüpft ist. Schreiben [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Setzt den Namen einer Form. Schreiben [System::String](../../system/string/). |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Schreiben **bool**. |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | Bestimmt, ob Audio wiederholt wird. Schreiben **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | Setzt den Audio-Wiedergabemodus. Schreiben [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Setzt die rohen Eigenschaften des Formrahmens. Schreiben [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | Setzt den Skalierungsfaktor der Höhe (relativ zur ursprünglichen Bildgröße) des Bildrahmens. Der Wert 1,0 entspricht 100 %. Schreiben **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | Setzt den Skalierungsfaktor der Breite (relativ zur ursprünglichen Bildgröße) des Bildrahmens. Der Wert 1,0 entspricht 100 %. Schreiben **float**. |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | Bestimmt, ob Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Schreiben **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Setzt die Drehung der angegebenen Form um die Z-Achse in Grad. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Gegen-Uhrzeigersinn. Schreiben **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Setzt den Geometrie-Voreinstellungstyp. Hinweis: Beim Ändern des Wertes werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Schreiben [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt wird, in Millisekunden. Schreiben **float**. |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | Gibt die Zeitdauer an, die am Anfang des Mediums während der Wiedergabe entfernt wird, in Millisekunden. Schreiben **float**. |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | Setzt die Audio-Lautstärke. Schreiben [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | Setzt die Audio-Lautstärke in Prozent. Schreiben **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Setzt die Breite der Form in Punkt. Schreiben **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Setzt die X-Koordinate der oberen linken Ecke der Form in Punkt. Schreiben **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Setzt die Y-Koordinate der oberen linken Ecke der Form in Punkt. Schreiben **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Aktualisiert die Formgeometrie aus dem [IGeometryPath](../igeometrypath/)-Objekt. Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Formtyp ([ShapeType](../shapetype/)) zu [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Aktualisiert die Formgeometrie aus einem Array von [IGeometryPath](../igeometrypath/). Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Formtyp ([ShapeType](../shapetype/)) zu [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Gegenstück zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C# lock()-Statement zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [IPictureFrame](../ipictureframe/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)