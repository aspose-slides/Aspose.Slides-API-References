---
title: LegacyDiagram
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt ein Legacy-Diagrammobjekt dar.
type: docs
weight: 4330
url: /de/aspose.slides/legacydiagram/
---
## LegacyDiagram Klasse

Stellt ein Legacy-Diagrammobjekt dar.

```cpp
class LegacyDiagram : public Aspose::Slides::GraphicalObject,
                      public Aspose::Slides::ILegacyDiagram
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [ConvertToGroupShape](./converttogroupshape/)() override | Konvertiert das Legacy-Diagramm in eine bearbeitbare Gruppierungsform. Das erstellte [GroupShape](../groupshape/)-Objekt wird der übergeordneten Gruppierungsform an derselben Position hinzugefügt. |
| [System::SharedPtr](../../system/sharedptr/)\<[SmartArt::ISmartArt](../../aspose.slides.smartart/ismartart/)\> [ConvertToSmartArt](./converttosmartart/)() override | Konvertiert das Legacy-Diagramm in ein bearbeitbares [SmartArt](../../aspose.slides.smartart/)-Objekt. Das erstellte [SmartArt](../../aspose.slides.smartart/)-Objekt wird der übergeordneten Gruppierungsform an derselben Position hinzugefügt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mithilfe der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Gibt den mit einer Form verbundenen Alternativtext zurück. Siehe [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Gibt den Titel des mit einer Form verbundenen Alternativtexts zurück. Siehe [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Die Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird. Siehe [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Gibt die Anzahl der Verbindungsstellen der Form zurück. Nur lesbar **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesbar [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Gibt das [EffectFormat](../effectformat/)-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: Kann bei bestimmten Formtypen, die keine Effekt-Eigenschaften besitzen, null zurückgeben. Nur lesbar [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Gibt das [FillFormat](../fillformat/)-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält. Hinweis: Kann bei bestimmten Formtypen, die keine Füll-Eigenschaften besitzen, null zurückgeben. Nur lesbar [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Gibt die Eigenschaften des Formrahmens zurück. Siehe [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Gibt die Sperren der Form zurück. Nur lesbar [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Ermittelt die Höhe der Form in Punkten. Nur lesbar **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Bestimmt, ob die Form ausgeblendet ist. Nur lesbar **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Gibt den für Mausklick definierten Hyperlink zurück. Siehe [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Gibt den Hyperlink-Manager zurück. Nur lesbar [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Gibt den für Mouse-Over definierten Hyperlink zurück. Siehe [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Ermittelt die Option „Als dekorativ markieren“. Lesen/Schreiben **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Bestimmt, ob die Form gruppiert ist. Nur lesbar **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Bestimmt, ob die Form TextHolder_PPT ist. Nur lesbar **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Gibt das [LineFormat](../lineformat/)-Objekt zurück, das Zeilenformatierungseigenschaften für eine Form enthält. Hinweis: Kann bei bestimmten Formtypen, die keine Zeileneigenschaften besitzen, null zurückgeben. Nur lesbar [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Gibt den Namen einer Form zurück. Darf nicht null sein. Verwenden Sie bei Bedarf den leeren Zeichenkettenwert. Siehe [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Gibt einen Folien-gebundenen eindeutigen Bezeichner zurück, der während der gesamten Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur lesbar **uint32_t**. Siehe auch [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Gibt das übergeordnete [GroupShape](../groupshape/)-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Gibt die rohen Eigenschaften des Formrahmens zurück. Siehe [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Rotation im Uhrzeigersinn; ein negativer Wert bedeutet Rotation gegen den Uhrzeigersinn. Nur lesbar **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Gibt die Sperren der Form zurück. Nur lesbar [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Gibt die übergeordnete Folie einer Form zurück. Nur lesbar [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Gibt das [ThreeDFormat](../threedformat/)-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält. Hinweis: Kann bei bestimmten Formtypen, die keine 3D-Eigenschaften besitzen, null zurückgeben. Nur lesbar [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Gibt einen internen, Präsentations-gebundenen Bezeichner zurück, der für Add-Ins oder anderen Code vorgesehen ist. Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden. Nur lesbar **uint32_t**. Siehe auch [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Ermittelt die Breite der Form in Punkten. Nur lesbar **float**. |
| **float** [get_X](../shape/get_x/)() override | Ermittelt die x-Koordinate der oberen linken Ecke der Form in Punkten. Nur lesbar **float**. |
| **float** [get_Y](../shape/get_y/)() override | Ermittelt die y-Koordinate der oberen linken Ecke der Form in Punkten. Nur lesbar **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der Z-Reihenfolge zurück. Nur lesbar **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Gibt eine einfache Platzhalter-Form zurück (eine Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Entspricht der C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Gibt das Form-Miniaturbild zurück. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) Bild-Grenztyp wird standardmäßig verwendet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Gibt das Form-Miniaturbild zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Entspricht dem C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Ermittelt die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Entspricht dem C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Entspricht der C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren in Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren in Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz einen Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definiert, dass diese Form kein Platzhalter ist. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Setzt den mit einer Form verbundenen Alternativtext. Schreiben [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Setzt den Titel des mit einer Form verbundenen Alternativtexts. Schreiben [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Die Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird. Schreiben [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Setzt die Eigenschaften des Formrahmens. Schreiben [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Setzt die Höhe der Form in Punkten. Schreiben **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Bestimmt, ob die Form ausgeblendet ist. Schreiben **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Setzt den für Mausklick definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Setzt den für Mouse-Over definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Setzt die Option „Als dekorativ markieren“. Lesen/Schreiben **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Setzt den Namen einer Form. Darf nicht null sein. Verwenden Sie bei Bedarf den leeren Zeichenkettenwert. Schreiben [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Setzt die rohen Eigenschaften des Formrahmens. Schreiben [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Setzt die Anzahl der Grad, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Schreiben **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Setzt die Breite der Form in Punkten. Schreiben **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Setzt die x-Koordinate der oberen linken Ecke der Form in Punkten. Schreiben **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Setzt die y-Koordinate der oberen linken Ecke der Form in Punkten. Schreiben **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Wechseln von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen intelligente Zeiger oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen intelligente Zeiger oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Entspricht der C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen intelligente Zeiger oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen intelligente Zeiger oder ThisProtector verwenden. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Speichert den Inhalt von [Shape](../shape/) als SVG-Datei. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [GraphicalObject](../graphicalobject/)
* Klasse [ILegacyDiagram](../ilegacydiagram/)
* Namespace [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)