---
title: TextFrameFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält die formatTextFrameFormatting-Eigenschaften des TextFrames.
type: docs
weight: 5461
url: /de/aspose.slides/textframeformat/
---
## TextFrameFormat Klasse

Enthält die formatTextFrameFormatting Eigenschaften von [TextFrame](../textframe/).

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergleicht mit dem angegebenen Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mittels C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Gibt den vertikalen Ankertext in einem [TextFrame](../textframe/) zurück. Lesen [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Gibt den Autofit-Modus des Textes zurück. Lesen [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Falls [NullableBool::True](../nullablebool/), wird der Text horizontal im Feld zentriert. Lesen [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Gibt die Anzahl der Spalten im Textbereich zurück. Dieser Wert muss positiv sein. Andernfalls wird er auf Null gesetzt. Wert 0 bedeutet undefinierten Wert. Lesen **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Gibt den Abstand zwischen Textspalten im Textbereich (in Punkt) zurück. Dies gilt nur, wenn mehr als eine Spalte vorhanden ist. Der Wert muss positiv sein. Andernfalls wird er auf Null gesetzt. Lesen **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Erhält, dass Text flach bleibt, selbst wenn ein 3-D-Rotations-Effekt angewendet wurde. Lesen **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Gibt den unteren Rand (Punkt) in einem [TextFrame](../textframe/) zurück. Lesen **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Gibt den linken Rand (Punkt) in einem [TextFrame](../textframe/) zurück. Lesen **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Gibt den rechten Rand (Punkt) in einem [TextFrame](../textframe/) zurück. Lesen **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Gibt den oberen Rand (Punkt) in einem [TextFrame](../textframe/) zurück. Lesen **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Gibt das übergeordnete [IPresentationComponent](../ipresentationcomponent/) zurück. Nur-Lesen [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Gibt die benutzerdefinierte Rotation an, die auf den Text im Begrenzungsrahmen angewendet wird. Wird sie nicht angegeben, wird die Rotation der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das heißt, die Form kann eine Rotation haben, zusätzlich zur Rotation des Textes. Der resultierende Wert der visuellen Textrotation ist aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammengefasst. Lesen **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Bestimmt die Textausrichtung. Der resultierende Wert der visuellen Textrotation ist aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle zusammengefasst. Lesen [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Gibt das [ThreeDFormat](../threedformat/)-Objekt zurück, das 3-D-Effekteigenschaften für einen Text darstellt. Nur-Lesen [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Ermittelt die Textumbruch-Form. Lesen [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True**, wenn der Text an den Rändern von [TextFrame](../textframe/) umbrochen wird. Lesen [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Erhält die effektiven Textframe-Formatierungsdaten mit angewandter Vererbung. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Gibt den Hash-Code zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentinelle-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktor-Verhalten für Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktor-Verhalten für Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzweise ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Setzt den vertikalen Ankertext in einem [TextFrame](../textframe/). Schreiben [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Setzt den Autofit-Modus des Textes. Schreiben [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Falls [NullableBool::True](../nullablebool/), wird der Text horizontal im Feld zentriert. Schreiben [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Setzt die Anzahl der Spalten im Textbereich. Dieser Wert muss positiv sein. Andernfalls wird er auf Null gesetzt. Wert 0 bedeutet undefinierten Wert. Schreiben **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Setzt den Abstand zwischen Textspalten im Textbereich (in Punkten). Dies gilt nur, wenn mehr als eine Spalte vorhanden ist. Der Wert muss positiv sein. Andernfalls wird er auf Null gesetzt. Schreiben **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Setzt, dass Text flach bleibt, selbst wenn ein 3-D-Rotations-Effekt angewendet wurde. Schreiben **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Setzt den unteren Rand (Punkt) in einem [TextFrame](../textframe/). Schreiben **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Setzt den linken Rand (Punkt) in einem [TextFrame](../textframe/). Schreiben **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Setzt den rechten Rand (Punkt) in einem [TextFrame](../textframe/). Schreiben **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Setzt den oberen Rand (Punkt) in einem [TextFrame](../textframe/). Schreiben **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Gibt die benutzerdefinierte Rotation an, die auf den Text im Begrenzungsrahmen angewendet wird. Wird sie nicht angegeben, wird die Rotation der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das heißt, die Form kann eine Rotation haben, zusätzlich zur Rotation des Textes. Der resultierende Wert der visuellen Textrotation ist aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammengefasst. Schreiben **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Bestimmt die Textausrichtung. Der resultierende Wert der visuellen Textrotation ist aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle zusammengefasst. Schreiben [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Setzt die Textumbruch-Form. Schreiben [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True**, wenn der Text an den Rändern von [TextFrame](../textframe/) umbrochen wird. Schreiben [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt zugeteilt). Ermöglicht das Wechseln von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [TextFrameFormat](./textframeformat/)() | Initialisiert eine neue Instanz der [TextFrameFormat](./) Klasse. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentinelle-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [PVIObject](../pviobject/)
* Klasse [ITextFrameFormat](../itextframeformat/)
* Klasse [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)