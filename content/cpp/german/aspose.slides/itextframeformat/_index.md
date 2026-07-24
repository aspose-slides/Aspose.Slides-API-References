---
title: ITextFrameFormat
second_title: Aspose.Slides für C++ API Referenz
description: Enthält die Formatierungseigenschaften des TextFrame.
type: docs
weight: 4083
url: /de/aspose.slides/itextframeformat/
---
## ITextFrameFormat Klasse

Enthält die Formatierungseigenschaften von [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte von Referenztypen im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte von Werttypen im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Gibt den vertikalen Ankertext in einem [TextFrame](../textframe/) zurück. Lesen [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Gibt den Autofit-Modus des Textes zurück. Lesen [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Wenn [NullableBool::True](../nullablebool/) dann sollte der Text horizontal im Feld zentriert werden. Lesen [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Gibt die Anzahl der Spalten im Textbereich zurück. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. Der Wert 0 bedeutet undefinierten Wert. Lesen **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Gibt den Abstand zwischen Textspalten im Textbereich (in Punkten) zurück. Dies sollte nur gelten, wenn mehr als eine Spalte vorhanden ist. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. Lesen **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Gibt zurück oder legt fest, dass Text vollständig von der 3D-Szene ausgeschlossen wird. Lesen **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Gibt den unteren Rand (Punkte) in einem [TextFrame](../textframe/) zurück. Lesen **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Gibt den linken Rand (Punkte) in einem [TextFrame](../textframe/) zurück. Lesen **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Gibt den rechten Rand (Punkte) in einem [TextFrame](../textframe/) zurück. Lesen **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Gibt den oberen Rand (Punkte) in einem [TextFrame](../textframe/) zurück. Lesen **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form eine Drehung erhalten kann zusätzlich zur Drehung des Textes selbst. Der resultierende Wert der visuellen Textdrehung wird aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammengefasst. Lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Gibt den Stil des Textes zurück. Nur-lesen [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Bestimmt die Textorientierung. Der resultierende Wert der visuellen Textdrehung wird aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle zusammengefasst. Lesen [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Gibt das [ThreeDFormat](../threedformat/)-Objekt zurück, das 3D-Effekteigenschaften für einen Text darstellt. Nur-lesen [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Ermittelt die Textumbruch-Form. Lesen [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** wenn der Text an den Rändern von [TextFrame](../textframe/) umbrochen wird. Lesen [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Ermittelt die wirksamen Textrahmen-Formatierungsdaten mit angewandter Vererbung. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C#-lock()-Statements. Direkter Aufruf oder Verwendung des [LockContext](../../system/lockcontext/)-Wächterobjekts. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Setzt den vertikalen Ankertext in einem [TextFrame](../textframe/). Schreiben [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Setzt den Autofit-Modus des Textes. Schreiben [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Wenn [NullableBool::True](../nullablebool/) dann sollte der Text horizontal im Feld zentriert werden. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Setzt die Anzahl der Spalten im Textbereich. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. Der Wert 0 bedeutet undefinierten Wert. Schreiben **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Setzt den Abstand zwischen Textspalten im Textbereich (in Punkten). Dies sollte nur gelten, wenn mehr als eine Spalte vorhanden ist. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. Schreiben **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Gibt zurück oder legt fest, dass Text vollständig von der 3D-Szene ausgeschlossen wird. Schreiben **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Setzt den unteren Rand (Punkte) in einem [TextFrame](../textframe/). Schreiben **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Setzt den linken Rand (Punkte) in einem [TextFrame](../textframe/). Schreiben **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Setzt den rechten Rand (Punkte) in einem [TextFrame](../textframe/). Schreiben **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Setzt den oberen Rand (Punkte) in einem [TextFrame](../textframe/). Schreiben **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form eine Drehung erhalten kann zusätzlich zur Drehung des Textes selbst. Der resultierende Wert der visuellen Textdrehung wird aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammengefasst. Schreiben **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Bestimmt die Textorientierung. Der resultierende Wert der visuellen Textdrehung wird aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle zusammengefasst. Schreiben [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Setzt die Textumbruch-Form. Schreiben [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** wenn der Text an den Rändern von [TextFrame](../textframe/) umbrochen wird. Schreiben [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument als schwachen Zeiger (statt geteilten). Ermöglicht das Wechseln von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht das Konvertieren benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkter Aufruf oder Verwendung des [LockContext](../../system/lockcontext/)-Wächterobjekts. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)