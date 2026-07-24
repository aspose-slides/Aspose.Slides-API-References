---
title: IVideoFrame
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Videoclip auf einer Folie dar.
type: docs
weight: 4226
url: /de/aspose.slides/ivideoframe/
---
## IVideoFrame Klasse

Stellt einen Videoclip auf einer Folie dar.

```cpp
class IVideoFrame : public virtual Aspose::Slides::IPictureFrame
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Erstellt und gibt ein Array von Form-Elementen zurück. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Gibt den Anpassungswert einer Form am angegebenen Index zurück. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Gibt eine Sammlung von Form-Anpassungswerten zurück. Nur lesbar [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Gibt den Alternativtext zurück, der einer Form zugeordnet ist. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Gibt den Titel des Alternativtextes zurück, der einer Form zugeordnet ist. Lesen [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Eigenschaft legt fest, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird. Lesen [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | Liefert die Sammlung von Untertiteln, die dem Audio-Frame zugeordnet sind. Diese Eigenschaft ist nur lesbar und gibt ein [ICaptionsCollection](../icaptionscollection/) zurück, das alle Untertitelspuren enthält. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Gibt die Anzahl der Verbindungsstellen der Form zurück. Nur lesbar **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesbar [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Gibt das [EffectFormat](../effectformat/)-Objekt zurück, das die auf eine Form angewendeten Pixeleffekte enthält. Nur lesbar [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() | Gibt das eingebettete Video-Objekt zurück. Lesen [IVideo](../ivideo/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Gibt das [FillFormat](../fillformat/)-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. Nur lesbar [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Gibt die Eigenschaften des Form-Frames zurück. Lesen [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_FullScreenMode](./get_fullscreenmode/)() | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Lesen **bool**. |
| virtual **float** [get_Height](../ishape/get_height/)() | Gibt die Höhe der Form in Punkt gemessen zurück. Lesen **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Bestimmt, ob die Form ausgeblendet ist. Lesen **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | Bestimmt, ob ein [VideoFrame](../videoframe/) ausgeblendet ist. Lesen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Gibt den für Mausklick definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlink-Verwalter Nur lesbar [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Gibt den für Maus-over definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Liest die Option 'Mark as decorative'. Lesen/Schreiben **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Bestimmt, ob die Form gruppiert ist. Nur lesbar **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Bestimmt, ob die Form ein TextHolder ist. Nur lesbar **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Gibt das [LineFormat](../lineformat/)-Objekt zurück, das Zeilenformatierungseigenschaften für eine Form enthält. Nur lesbar [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Gibt den Namen einer Videodatei zurück, die mit einem [VideoFrame](../videoframe/) verknüpft ist. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Gibt den Namen einer Form zurück. Lesen [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur lesbar **uint32_t**. Siehe auch [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Gibt das übergeordnete [GroupShape](../groupshape/)-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | Gibt das [PictureFillFormat](../picturefillformat/)-Objekt für einen Bildrahmen zurück. Nur lesbar [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | Gibt die Sperren von [PictureFrame](../pictureframe/) zurück. Nur lesbar [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Gibt den Platzhalter für eine Form zurück. Nur lesbar [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | Bestimmt, ob ein Video wiederholt wird. Lesen **bool**. |
| virtual [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() | Gibt den Videowiedergabemodus zurück. Lesen [VideoPlayModePreset](../videoplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Gibt die Präsentation zurück. Nur lesbar [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Gibt die rohen Eigenschaften des Form-Frames zurück. Lesen [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | Gibt den Skalierungsfaktor der Höhe (relativ zur Originalbildgröße) des Bildrahmens zurück. Der Wert 1,0 entspricht 100 %. Lesen **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | Gibt den Skalierungsfaktor der Breite (relativ zur Originalbildgröße) des Bildrahmens zurück. Der Wert 1,0 entspricht 100 %. Lesen **float**. |
| virtual **bool** [get_RewindVideo](./get_rewindvideo/)() | Bestimmt, ob ein Video automatisch zum Anfang zurückgespult wird, sobald das Abspielen beendet ist. Lesen **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Gibt die Sperren der Form zurück. Nur lesbar [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Gibt das Stil-Objekt der Form zurück. Nur lesbar [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Gibt den Geometrie-Voreinstellungs-Typ zurück. Hinweis: Beim Ändern des Wertes werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lesen [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Gibt die Basis-Folien zurück. Nur lesbar [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Gibt das [ThreeDFormat](../threedformat/)-Objekt zurück, das Zeilenformatierungseigenschaften für eine Form enthält. Nur lesbar [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | Trim-Ende [ms] |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | Trim-Start [ms] |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als permanenter eindeutiger Schlüssel behandelt werden. Nur lesbar **uint32_t**. Siehe auch [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | Gibt die Audio-Lautstärke zurück. Lesen [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Gibt die Breite der Form in Punkt gemessen zurück. Lesen **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Gibt die X-Koordinate der oberen linken Ecke der Form in Punkt gemessen zurück. Lesen **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Gibt die Y-Koordinate der oberen linken Ecke der Form in Punkt gemessen zurück. Lesen **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] liefert die Form ganz hinten in der Z-Reihenfolge, und Shapes[Shapes.Count - 1] liefert die Form ganz vorne. Nur lesbar **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout- und/oder Master-Folien, von der die aktuelle Form erbt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Gibt eine Kopie des Pfads der Geometrie-Form zurück. Die Koordinaten sind relativ zur linken oberen Ecke der Form. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Gibt das Form-Vorschaubild zurück. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) Form-Vorschaubild-Grenztyp wird standardmäßig verwendet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Gibt das Form-Vorschaubild zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts wirklich, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts wirklich, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definiert, dass diese Form kein Platzhalter ist. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Setzt den Alternativtext, der einer Form zugeordnet ist. Schreiben [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Setzt den Titel des Alternativtextes, der einer Form zugeordnet ist. Schreiben [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Eigenschaft legt fest, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird. Schreiben [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) | Setzt das eingebettete Video-Objekt. Schreiben [IVideo](../ivideo/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Setzt die Eigenschaften des Form-Frames. Schreiben [IShapeFrame](../ishapeframe/). |
| virtual void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Schreiben **bool**. |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Setzt die Höhe der Form in Punkten. Schreiben **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Bestimmt, ob die Form ausgeblendet ist. Schreiben **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | Bestimmt, ob ein [VideoFrame](../videoframe/) ausgeblendet ist. Schreiben **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Setzt den für Mausklick definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Setzt den für Maus-over definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Setzt die Option 'Mark as decorative'. Lesen/Schreiben **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Setzt den Namen einer Videodatei, die mit einem [VideoFrame](../videoframe/) verknüpft ist. Schreiben [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Setzt den Namen einer Form. Schreiben [System::String](../../system/string/). |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | Bestimmt, ob ein Video wiederholt wird. Schreiben **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) | Setzt den Videowiedergabemodus. Schreiben [VideoPlayModePreset](../videoplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Setzt die rohen Eigenschaften des Form-Frames. Schreiben [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | Setzt den Skalierungsfaktor der Höhe (relativ zur Originalbildgröße) des Bildrahmens. Der Wert 1,0 entspricht 100 %. Schreiben **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | Setzt den Skalierungsfaktor der Breite (relativ zur Originalbildgröße) des Bildrahmens. Der Wert 1,0 entspricht 100 %. Schreiben **float**. |
| virtual void [set_RewindVideo](./set_rewindvideo/)(**bool**) | Bestimmt, ob ein Video automatisch zum Anfang zurückgespult wird, sobald das Abspielen beendet ist. Schreiben **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Setzt die Anzahl der Grad, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Schreiben **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Setzt den Geometrie-Voreinstellungs-Typ. Hinweis: Beim Ändern des Wertes werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Schreiben [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | Trim-Ende [ms] |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | Trim-Start [ms] |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | Setzt die Audio-Lautstärke. Schreiben [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Setzt die Breite der Form in Punkten. Schreiben **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Setzt die X-Koordinate der oberen linken Ecke der Form in Punkten. Schreiben **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Setzt die Y-Koordinate der oberen linken Ecke der Form in Punkten. Schreiben **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Aktualisiert die Formgeometrie aus dem [IGeometryPath](../igeometrypath/)-Objekt. Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([ShapeType](../shapetype/)) zu [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Aktualisiert die Formgeometrie aus einem Array von [IGeometryPath](../igeometrypath/). Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([ShapeType](../shapetype/)) zu [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Vorlagenargument zu einem schwachen Zeiger (statt shared). Ermöglicht das Umstellen von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des geteilten Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die geteilte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die geteilte Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IPictureFrame](../ipictureframe/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)