---
title: IPictureFrame
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Rahmen mit einem Bild im Inneren dar.
type: docs
weight: 3251
url: /de/aspose.slides/ipictureframe/
---
## IPictureFrame Klasse

Represents a frame with a picture inside.

```cpp
class IPictureFrame : public virtual Aspose::Slides::IGeometryShape
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Erstellt und gibt ein Array der shape-Elemente zurück. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte vom Referenztyp im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte vom Werttyp im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, wobei zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, wobei zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Gibt den Anpassungswert einer shape am angegebenen Index zurück. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Gibt eine Sammlung von shape-Anpassungswerten zurück. Nur-Lesen [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Gibt den alternativen Text, der einer shape zugeordnet ist, zurück. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Gibt den Titel des alternativen Textes, der einer shape zugeordnet ist, zurück. Lesen [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Eigenschaft legt fest, wie eine shape im Schwarz-Weiß-Anzeigemodus gerendert wird. Lesen [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Gibt die Anzahl der Verbindungspunkte der shape zurück. Nur-Lesen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Gibt die benutzerdefinierten Daten der shape zurück. Nur-Lesen [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Gibt das [EffectFormat](../effectformat/)-Objekt zurück, das Pixeleffekte enthält, die auf eine shape angewendet werden. Nur-Lesen [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Gibt das [FillFormat](../fillformat/)-Objekt zurück, das Füllformatierungseigenschaften für eine shape enthält. Nur-Lesen [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Gibt die Eigenschaften des shape-Frames zurück. Lesen [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Ermittelt die Höhe der shape, gemessen in Punkten. Lesen **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Bestimmt, ob die shape verborgen ist. Lesen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Gibt den für Mausklick definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlink-Manager Nur-Lesen [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Gibt den für Mausüberfahren definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Ermittelt die Option 'Mark as decorative' Lese/Schreiben **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Bestimmt, ob die shape gruppiert ist. Nur-Lesen **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Bestimmt, ob die shape ein TextHolder ist. Nur-Lesen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Gibt das [LineFormat](../lineformat/)-Objekt zurück, das Zeilenformatierungseigenschaften für eine shape enthält. Nur-Lesen [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Gibt den Namen einer shape zurück. Lesen [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der während der Lebensdauer der shape konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die shape zuverlässig von überall im Dokument zu referenzieren. Nur-Lesen **uint32_t**. Siehe auch [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Gibt das übergeordnete [GroupShape](../groupshape/)-Objekt zurück, wenn die shape gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lesen [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() | Gibt das [PictureFillFormat](../picturefillformat/)-Objekt für einen Bildrahmen zurück. Nur-Lesen [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() | Gibt die Sperren von [PictureFrame](../pictureframe/) zurück. Nur-Lesen [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Gibt den Platzhalter für eine shape zurück. Nur-Lesen [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Gibt die Präsentation zurück. Nur-Lesen [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Gibt die rohen Eigenschaften des shape-Frames zurück. Lesen [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() | Gibt den Höhenmaßstab (relativ zur Originalbildgröße) des Bildrahmens zurück. Der Wert 1,0 entspricht 100 %. Lesen **float**. |
| virtual **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() | Gibt den Breitenmaßstab (relativ zur Originalbildgröße) des Bildrahmens zurück. Der Wert 1,0 entspricht 100 %. Lesen **float**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Gibt die Anzahl der Grad zurück, um die die angegebene shape um die z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Gibt die Sperren der shape zurück. Nur-Lesen [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Gibt das Stil-Objekt der shape zurück. Nur-Lesen [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Gibt den vordefinierten Geometrie-Typ zurück. Hinweis: Beim Ändern des Werts werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lesen [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Gibt die Basisfolie zurück. Nur-Lesen [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Gibt das [ThreeDFormat](../threedformat/)-Objekt zurück, das Zeilenformatierungseigenschaften für eine shape enthält. Nur-Lesen [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Gibt einen internen, präsentionbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als permanenter eindeutiger Schlüssel betrachtet werden. Nur-Lesen **uint32_t**. Siehe auch [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Ermittelt die Breite der shape, gemessen in Punkten. Lesen **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Ermittelt die x-Koordinate der oberen linken Ecke der shape, gemessen in Punkten. Lesen **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Ermittelt die y-Koordinate der oberen linken Ecke der shape, gemessen in Punkten. Lesen **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Gibt die Position einer shape in der Z-Reihenfolge zurück. Shapes[0] liefert die shape ganz hinten in der Z-Reihenfolge, und Shapes[Shapes.Count - 1] liefert die shape ganz vorne. Nur-Lesen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Gibt eine grundlegende Platzhalter-shape zurück (shape aus dem Layout und/oder der Master-Folie, von der die aktuelle shape erbt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Gibt die Kopie des Pfads der Geometrie-shape zurück. Koordinaten sind relativ zur linken oberen Ecke der shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Gibt das Shape-Thumbnail zurück. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) Shape-Thumbnail-Bounds-Typ wird standardmäßig verwendet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Gibt das Shape-Thumbnail zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Objekt vom Werttyp per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definiert, dass diese shape kein Platzhalter ist. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Setzt den alternativen Text, der einer shape zugeordnet ist. Schreiben [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Setzt den Titel des alternativen Textes, der einer shape zugeordnet ist. Schreiben [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Eigenschaft legt fest, wie eine shape im Schwarz-Weiß-Anzeigemodus gerendert wird. Schreiben [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Setzt die Eigenschaften des shape-Frames. Schreiben [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Setzt die Höhe der shape, gemessen in Punkten. Schreiben **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Legt fest, ob die shape verborgen ist. Schreiben **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Setzt den für Mausklick definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Setzt den für Mausüberfahren definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Setzt die Option 'Mark as decorative' Lese/Schreiben **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Setzt den Namen einer shape. Schreiben [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Setzt die rohen Eigenschaften des shape-Frames. Schreiben [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) | Setzt den Höhenmaßstab (relativ zur Originalbildgröße) des Bildrahmens. Der Wert 1,0 entspricht 100 %. Schreiben **float**. |
| virtual void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) | Setzt den Breitenmaßstab (relativ zur Originalbildgröße) des Bildrahmens. Der Wert 1,0 entspricht 100 %. Schreiben **float**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Setzt die Anzahl der Grad, um die die angegebene shape um die z-Achse gedreht wird. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Schreiben **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Setzt den vordefinierten Geometrie-Typ. Hinweis: Beim Ändern des Werts werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Schreiben [Slides::ShapeType](../shapetype/). |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Setzt die Breite der shape, gemessen in Punkten. Schreiben **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Setzt die x-Koordinate der oberen linken Ecke der shape, gemessen in Punkten. Schreiben **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Setzt die y-Koordinate der oberen linken Ecke der shape, gemessen in Punkten. Schreiben **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Aktualisiert die Geometrie der shape aus dem [IGeometryPath](../igeometrypath/)-Objekt. Koordinaten müssen relativ zur linken oberen Ecke der shape sein. Ändert den Typ der shape ([ShapeType](../shapetype/)) zu [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Aktualisiert die Geometrie der shape aus einem Array von [IGeometryPath](../igeometrypath/). Koordinaten müssen relativ zur linken oberen Ecke der shape sein. Ändert den Typ der shape ([ShapeType](../shapetype/)) zu [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsam genutzten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsam genutzte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsam genutzte Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte zu einem String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe Auch

* Klasse [IGeometryShape](../igeometryshape/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)