---
title: PictureFrame
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Rahmen mit einem Bild im Inneren dar.
type: docs
weight: 4733
url: /de/aspose.slides/pictureframe/
---
## PictureFrame Klasse


Stellt einen Rahmen mit einem Bild im Inneren dar.

```cpp
class PictureFrame : public Aspose::Slides::GeometryShape,
                     public virtual Aspose::Slides::IPictureFrame
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und legt die Platzhalter-Eigenschaften auf einen angegebenen fest. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Erstellt und gibt ein Array von Shape-Elementen zurück. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für den internen Gebrauch. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Gibt den Anpassungswert eines Shapes am angegebenen Index zurück. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Gibt eine Sammlung von Anpassungswerten eines Shapes zurück. Nur lesbar [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Gibt den zu einem Shape zugehörigen Alternativtext zurück. Lesen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Gibt den Titel des zu einem Shape zugehörigen Alternativtexts zurück. Lesen [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Eigenschaft gibt an, wie ein Shape im Schwarz-weiß-Anzeige-Modus gerendert wird.. Lesen [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Gibt die Anzahl der Verbindungsstellen des Shapes zurück. Nur lesbar **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Gibt die benutzerdefinierten Daten des Shapes zurück. Nur lesbar [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Gibt das [EffectFormat](../effectformat/)-Objekt zurück, das Pixeleffekte enthält, die auf einen Shape angewendet werden. Hinweis: Kann für bestimmte Shape-Typen, die keine Effekt-Eigenschaften besitzen, null zurückgeben. Nur lesbar [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Gibt das [FillFormat](../fillformat/)-Objekt zurück, das Füllformatierungs-Eigenschaften für einen Shape enthält. Hinweis: Kann für bestimmte Shape-Typen, die keine Füll-Eigenschaften besitzen, null zurückgeben. Nur lesbar [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Gibt die Eigenschaften des Shape-Frames zurück. Lesen [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Ermittelt die Höhe des Shapes, gemessen in Punkten. Lesen **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Ermittelt, ob das Shape ausgeblendet ist. Lesen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Gibt den für Mausklick definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Gibt den Hyperlink-Manager zurück. Nur lesbar [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Gibt den für Mouse-Over definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](./get_iscameo/)() | Ermittelt, ob das [PictureFrame](./) ein Cameo-Objekt ist oder nicht. Nur lesbar **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Lies/Schreib die Option 'Mark as decorative' **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Ermittelt, ob das Shape gruppiert ist. Nur lesbar **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Ermittelt, ob das Shape TextHolder_PPT ist. Nur lesbar **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Gibt das [LineFormat](../lineformat/)-Objekt zurück, das Zeilenformatierungs-Eigenschaften für einen Shape enthält. Hinweis: Kann für bestimmte Shape-Typen, die keine Zeilen-Eigenschaften besitzen, null zurückgeben. Nur lesbar [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Gibt den Namen eines Shapes zurück. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Lesen [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der während der Lebensdauer des Shapes konstant bleibt und PowerPoint oder Interop-Code ermöglicht, das Shape von überall im Dokument zuverlässig zu referenzieren. Nur lesbar **uint32_t**. Siehe auch [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Gibt das übergeordnete [GroupShape](../groupshape/)-Objekt zurück, wenn das Shape gruppiert ist. Andernfalls null. Nur lesbar [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() override | Gibt das [PictureFillFormat](../picturefillformat/)-Objekt für einen Bildrahmen zurück. Nur lesbar [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() override | Gibt die Sperren des Shapes zurück. Nur lesbar [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Gibt den Platzhalter für ein Shape zurück. Gibt null zurück, wenn das Shape keinen Platzhalter hat. Nur lesbar [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Gibt die rohen Eigenschaften des Shape-Frames zurück. Lesen [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() override | Gibt die Skalierung der Höhe (relativ zur Originalbildgröße) des Bildrahmens zurück. Der Wert 1,0 entspricht 100 %. Lesen **float**. |
| **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() override | Gibt die Skalierung der Breite (relativ zur Originalbildgröße) des Bildrahmens zurück. Der Wert 1,0 entspricht 100 %. Lesen **float**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Gibt die Anzahl der Grad zurück, um die das angegebene Shape um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Gibt die Sperren des Shapes zurück. Nur lesbar [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Gibt das Style-Objekt des Shapes zurück. Nur lesbar [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Gibt die übergeordnete Folie eines Shapes zurück. Nur lesbar [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Gibt das [ThreeDFormat](../threedformat/)-Objekt zurück, das 3D-Effekt-Eigenschaften für einen Shape enthält. Hinweis: Kann für bestimmte Shape-Typen, die keine 3D-Eigenschaften besitzen, null zurückgeben. Nur lesbar [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code bestimmt ist. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel verwendet werden. Nur lesbar **uint32_t**. Siehe auch [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Ermittelt die Breite des Shapes, gemessen in Punkten. Lesen **float**. |
| **float** [get_X](../shape/get_x/)() override | Ermittelt die X-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten. Lesen **float**. |
| **float** [get_Y](../shape/get_y/)() override | Ermittelt die Y-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten. Lesen **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Gibt die Position eines Shapes in der Z-Reihenfolge zurück. Shapes[0] gibt das Shape ganz hinten in der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt das Shape ganz vorne zurück. Nur lesbar **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Gibt ein einfaches Platzhalter-Shape zurück (ein Shape aus dem Layout und/oder der Master-Folien, von dem das aktuelle Shape erbt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Gibt eine Kopie des Pfads des Geometrie-Shapes zurück. Die Koordinaten sind relativ zur linken oberen Ecke des Shapes. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Gibt das Shape-Thumbnail zurück. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) Shape-Thumbnail-Bounds-Typ wird standardmäßig verwendet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Gibt das Shape-Thumbnail zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Ermittelt die visuellen Grenzen des Shapes, berechnet aus dessen gerendertem Inhalt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich das neue Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich das neue Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzweise ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die geteilte Referenzzählung um den angegebenen Wert. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definiert, dass dieses Shape kein Platzhalter ist. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Setzt den zu einem Shape zugehörigen Alternativtext. Schreiben [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Setzt den Titel des zu einem Shape zugehörigen Alternativtexts. Schreiben [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Eigenschaft gibt an, wie ein Shape im Schwarz-weiß-Anzeige-Modus gerendert wird.. Schreiben [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Setzt die Eigenschaften des Shape-Frames. Schreiben [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Setzt die Höhe des Shapes, gemessen in Punkten. Schreiben **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Bestimmt, ob das Shape ausgeblendet ist. Schreiben **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Setzt den für Mausklick definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Setzt den für Mouse-Over definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Setzt die Option 'Mark as decorative'. Lesen/Schreiben **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Setzt den Namen eines Shapes. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Schreiben [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Setzt die rohen Eigenschaften des Shape-Frames. Schreiben [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) override | Setzt die Skalierung der Höhe (relativ zur Originalbildgröße) des Bildrahmens. Der Wert 1,0 entspricht 100 %. Schreiben **float**. |
| void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) override | Setzt die Skalierung der Breite (relativ zur Originalbildgröße) des Bildrahmens. Der Wert 1,0 entspricht 100 %. Schreiben **float**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Setzt die Anzahl der Grad, um die das angegebene Shape um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Schreiben **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_Width](../shape/set_width/)(**float**) override | Setzt die Breite des Shapes, gemessen in Punkten. Schreiben **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Setzt die X-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten. Schreiben **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Setzt die Y-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten. Schreiben **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Aktualisiert die Geometrie des Shapes aus dem [IGeometryPath](../igeometrypath/)-Objekt. Die Koordinaten müssen relativ zur linken oberen Ecke des Shapes sein. Ändert den Typ des Shapes ([ShapeType](../shapetype/)) zu [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Aktualisiert die Geometrie des Shapes aus einem Array von [IGeometryPath](../igeometrypath/). Die Koordinaten müssen relativ zur linken oberen Ecke des Shapes sein. Ändert den Typ des Shapes ([ShapeType](../shapetype/)) zu [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen weak-Pointer (statt shared). Ermöglicht das Wechseln von Pointern in Containern in den weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die geteilte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die geteilte Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Anmerkungen

Das folgende Beispiel zeigt, wie man das [Audio](../audio/) Frame Thumbnail ändert. 
```cpp
auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Fügt dem Folie einen Audio-Frame mit einer angegebenen Position und Größe hinzu.
auto audioStream = System::MakeObject<System::IO::FileStream>(u"sample2.mp3", System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(150.0f, 100.0f, 50.0f, 50.0f, audioStream);
audioStream->Dispose();

// Fügt ein Bild zu den Präsentationsressourcen hinzu.
auto imageStream = System::IO::File::OpenRead(u"eagle.jpeg");
auto audioImage = presentation->get_Images()->AddImage(imageStream);
imageStream->Dispose();

// Setzt das Bild für den Audio-Frame.
audioFrame->get_PictureFormat()->get_Picture()->set_Image(audioImage);

//Speichert die modifizierte Präsentation auf die Festplatte
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [GeometryShape](../geometryshape/)
* Klasse [IPictureFrame](../ipictureframe/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)