---
title: Shape
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
weight: 5084
url: /de/aspose.slides/shape/
---
## Shape Klasse

Stellt eine Form auf einer Folie dar.

```cpp
class Shape : public virtual Aspose::Slides::IShape,
              public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN mit keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN mit keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() override | Gibt den alternativen Text zurück, der mit einer Form verknüpft ist. Siehe [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() override | Gibt den Titel des alternativen Textes zurück, der mit einer Form verknüpft ist. Siehe [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() override | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird. Siehe [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() override | Gibt die Anzahl der Anschlussstellen der Form zurück. Nur lesbar **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesbar [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Gibt das [EffectFormat](../effectformat/)-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet wurden. Hinweis: Kann für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen, null zurückgeben. Nur lesbar [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Gibt das [FillFormat](../fillformat/)-Objekt zurück, das Füllformatierungs-Eigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen, null zurückgeben. Nur lesbar [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() override | Gibt die Eigenschaften des Formrahmens zurück. Siehe [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](./get_height/)() override | Ermittelt die Höhe der Form in Punkten. Nur lesbar **float**. |
| **bool** [get_Hidden](./get_hidden/)() override | Bestimmt, ob die Form ausgeblendet ist. Nur lesbar **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Gibt den für Mausklick definierten Hyperlink zurück. Siehe [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Gibt den Hyperlink-Manager zurück. Nur lesbar [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Gibt den für Maus-over definierten Hyperlink zurück. Siehe [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](./get_isdecorative/)() override | Liefert die Option 'Als dekorativ kennzeichnen'. Lese/Schreib **bool**. |
| **bool** [get_IsGrouped](./get_isgrouped/)() override | Bestimmt, ob die Form gruppiert ist. Nur lesbar **bool**. |
| **bool** [get_IsTextHolder](./get_istextholder/)() override | Bestimmt, ob die Form TextHolder_PPT ist. Nur lesbar **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Gibt das [LineFormat](../lineformat/)-Objekt zurück, das Zeilenformatierungs-Eigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine Zeilen-Eigenschaften besitzen, null zurückgeben. Nur lesbar [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Gibt den Namen einer Form zurück. Darf nicht null sein. Verwende bei Bedarf einen leeren Zeichenkettenwert. Siehe [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() override | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur lesbar **uint32_t**. Siehe auch [Shape::get_UniqueId](./get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | Gibt das übergeordnete [GroupShape](../groupshape/)-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() override | Gibt den Platzhalter einer Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() override | Gibt die Roh-Rahmeneigenschaften der Form zurück. Siehe [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](./get_rotation/)() override | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Nur lesbar **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() override | Gibt die Sperren der Form zurück. Nur lesbar [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Gibt die übergeordnete Folie einer Form zurück. Nur lesbar [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Gibt das [ThreeDFormat](../threedformat/)-Objekt zurück, das 3D-Effekteigenschaften einer Form enthält. Hinweis: Kann für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen, null zurückgeben. Nur lesbar [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](./get_uniqueid/)() override | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel verwendet werden. Nur lesbar **uint32_t**. Siehe auch [Shape::get_OfficeInteropShapeId](./get_officeinteropshapeid/). |
| **float** [get_Width](./get_width/)() override | Ermittelt die Breite der Form in Punkten. Nur lesbar **float**. |
| **float** [get_X](./get_x/)() override | Ermittelt die x-Koordinate der oberen linken Ecke der Form in Punkten. Nur lesbar **float**. |
| **float** [get_Y](./get_y/)() override | Ermittelt die y-Koordinate der oberen linken Ecke der Form in Punkten. Nur lesbar **float**. |
| **int32_t** [get_ZOrderPosition](./get_zorderposition/)() override | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende zurück. Nur lesbar **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](./getbaseplaceholder/)() override | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | Gibt die Miniaturansicht der Form zurück. Der Standard-Typ für die Miniaturansichts-Grenzen ist [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Gibt die Miniaturansicht der Form zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](./getvisualbounds/)() | Ermittelt die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts wirklich, initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Subklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts wirklich, initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Subklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [RemovePlaceholder](./removeplaceholder/)() override | Definiert, dass diese Form kein Platzhalter ist. |
| void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) override | Setzt den alternativen Text, der mit einer Form verknüpft ist. Schreiben [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) override | Setzt den Titel des alternativen Textes, der mit einer Form verknüpft ist. Schreiben [System::String](../../system/string/). |
| void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird. Schreiben [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Setzt die Eigenschaften des Formrahmens. Schreiben [IShapeFrame](../ishapeframe/). |
| void [set_Height](./set_height/)(**float**) override | Setzt die Höhe der Form in Punkten. Schreiben **float**. |
| void [set_Hidden](./set_hidden/)(**bool**) override | Bestimmt, ob die Form ausgeblendet ist. Schreiben **bool**. |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Setzt den für Mausklick definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Setzt den für Maus-over definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](./set_isdecorative/)(**bool**) override | Setzt die Option 'Als dekorativ kennzeichnen'. Schreiben **bool**. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Setzt den Namen einer Form. Darf nicht null sein. Verwende bei Bedarf einen leeren Zeichenkettenwert. Schreiben [System::String](../../system/string/). |
| void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Setzt die Roh-Rahmeneigenschaften der Form. Schreiben [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](./set_rotation/)(**float**) override | Setzt die Anzahl der Grad, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Schreiben **float**. |
| void [set_Width](./set_width/)(**float**) override | Setzt die Breite der Form in Punkten. Schreiben **float**. |
| void [set_X](./set_x/)(**float**) override | Setzt die x-Koordinate der oberen linken Ecke der Form in Punkten. Schreiben **float**. |
| void [set_Y](./set_y/)(**float**) override | Setzt die y-Koordinate der oberen linken Ecke der Form in Punkten. Schreiben **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Speichert den Inhalt von [Shape](./) als SVG-Datei. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Speichert den Inhalt von [Shape](./) als SVG-Datei. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe Auch

* Klasse [IShape](../ishape/)
* Klasse [IDOMObject](../idomobject/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)