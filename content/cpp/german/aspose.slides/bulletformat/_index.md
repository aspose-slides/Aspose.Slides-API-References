---
title: BulletFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Aufzählungszeichen-Formatierungseigenschaften eines Absatzes dar.
type: docs
weight: 248
url: /de/aspose.slides/bulletformat/
---
## BulletFormat Klasse

Stellt die Formatierungseigenschaften von Aufzählungszeichen für Absätze dar.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Setzt standardmäßige nicht-null Verschiebungen für den effektiven Absatz-Indent und MarginLeft, wenn Aufzählungszeichen aktiviert sind (wie PowerPoint es tut, wenn Absatz-Aufzählungszeichen/Nummerierung aktiviert werden). Wenn Aufzählungszeichen deaktiviert sind, werden lediglich Absatz-Indent und MarginLeft zurückgesetzt (wie PowerPoint es tut, wenn Absatz-Aufzählungszeichen/Nummerierung deaktiviert werden). Die Indent-Verschiebungen werden in Bezug auf den aktuellen Aufzählungskontext angewendet – IBulletFormat::get(set)_Type, .NumberedBulletStyle und FontHeight des ersten Abschnitts. Nicht-null Indent-Verschiebungen werden auf den effektiven Indent und MarginLeft des aktuellen Absatzes angewendet (damit die Ergebniswerte lokale Werte sind). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergleicht mit dem angegebenen Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte gemäß C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte vom Referenztyp im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| char16_t [get_Char](./get_char/)() override | Gibt das Aufzählungszeichen-Zeichen eines Absatzes ohne Vererbung zurück. Lesen **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Gibt das Farbformat eines Aufzählungszeichens eines Absatzes ohne Vererbung zurück. Nur-Lese [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Gibt die Schriftart des Aufzählungszeichens eines Absatzes ohne Vererbung zurück. Lesen [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Gibt die Höhe des Aufzählungszeichens eines Absatzes ohne Vererbung zurück. Der Wert std::numeric_limits<float>::quiet_NaN() bestimmt, dass das Aufzählungszeichen die Höhe vom ersten Teil des Absatzes erbt. Lesen **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Bestimmt, ob das Aufzählungszeichen eine eigene Farbe hat oder sie vom ersten Teil des Absatzes erbt. **[NullableBool::True](../nullablebool/)** wenn das Aufzählungszeichen eine eigene Farbe hat und **[NullableBool::False](../nullablebool/)** wenn das Aufzählungszeichen die Farbe vom ersten Teil des Absatzes erbt. Lesen [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Bestimmt, ob das Aufzählungszeichen eine eigene Schriftart hat oder sie vom ersten Teil des Absatzes erbt. **[NullableBool::True](../nullablebool/)** wenn das Aufzählungszeichen eine eigene Schriftart hat und **[NullableBool::False](../nullablebool/)** wenn das Aufzählungszeichen die Schriftart vom ersten Teil des Absatzes erbt. Lesen [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Gibt die erste Nummer zurück, die für eine Gruppe nummerierter Aufzählungszeichen ohne Vererbung verwendet wird. Lesen **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Gibt den Stil eines nummerierten Aufzählungszeichens ohne Vererbung zurück. Lesen [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Gibt das Objekt Parent_Immediate zurück. Nur-Lese [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Gibt den übergeordneten [IPresentationComponent](../ipresentationcomponent/) zurück. Nur-Lese [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Gibt das Bild zurück, das als Aufzählungszeichen in einem Absatz ohne Vererbung verwendet wird. Nur-Lese [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Gibt den Aufzählungszeichentyp eines Absatzes ohne Vererbung zurück. Lesen [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Datenstruktur des Referenzzählers ab, die dem Objekt zugeordnet ist. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Ruft die effektiven Aufzählungsformatierungsdaten ab, bei denen die Vererbung angewendet wurde. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Gibt den Hash-Code zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zu C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Char](./set_char/)(char16_t) override | Setzt das Aufzählungszeichen-Zeichen eines Absatzes ohne Vererbung. Schreiben **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Setzt die Schriftart des Aufzählungszeichens eines Absatzes ohne Vererbung. Schreiben [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Setzt die Höhe des Aufzählungszeichens eines Absatzes ohne Vererbung. Der Wert std::numeric_limits<float>::quiet_NaN() bestimmt, dass das Aufzählungszeichen die Höhe vom ersten Teil des Absatzes erbt. Schreiben **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Bestimmt, ob das Aufzählungszeichen eine eigene Farbe hat oder sie vom ersten Teil des Absatzes erbt. **[NullableBool::True](../nullablebool/)** wenn das Aufzählungszeichen eine eigene Farbe hat und **[NullableBool::False](../nullablebool/)** wenn das Aufzählungszeichen die Farbe vom ersten Teil des Absatzes erbt. Schreiben [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Bestimmt, ob das Aufzählungszeichen eine eigene Schriftart hat oder sie vom ersten Teil des Absatzes erbt. **[NullableBool::True](../nullablebool/)** wenn das Aufzählungszeichen eine eigene Schriftart hat und **[NullableBool::False](../nullablebool/)** wenn das Aufzählungszeichen die Schriftart vom ersten Teil des Absatzes erbt. Schreiben [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Setzt die erste Nummer, die für eine Gruppe nummerierter Aufzählungszeichen ohne Vererbung verwendet wird. Schreiben **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Setzt den Stil eines nummerierten Aufzählungszeichens ohne Vererbung. Schreiben [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Setzt den Aufzählungszeichentyp eines Absatzes ohne Vererbung. Schreiben [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [PVIObject](../pviobject/)
* Klasse [IBulletFormat](../ibulletformat/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)