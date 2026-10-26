---
title: IBulletFormat
second_title: Aspose.Slides für C++ API Referenz
description: Stellt die Aufzählungszeichen-Formatierungseigenschaften eines Absatzes dar.
type: docs
weight: 1561
url: /de/aspose.slides/ibulletformat/
---
## IBulletFormat Klasse

Stellt die Aufzählungszeichen-Formatierungseigenschaften eines Absatzes dar.

```cpp
class IBulletFormat : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | Setzt standardmäßige nicht-null Verschiebungen für den wirksamen Absatz-Indent und MarginLeft, wenn Aufzählungszeichen aktiviert sind (wie PowerPoint es tut, wenn Absatz-Aufzählungszeichen/Nummerierung aktiviert werden). Wenn Aufzählungszeichen deaktiviert sind, werden lediglich Absatz-Indent und MarginLeft zurückgesetzt (wie PowerPoint es tut, wenn Absatz-Aufzählungszeichen/Nummerierung deaktiviert werden). Indent-Verschiebungen werden in Bezug auf den aktuellen Aufzählungskontext angewendet – IBulletFormat::get(set)_Type, .NumberedBulletStyle und FontHeight des ersten Abschnitts. Nicht-null Indent-Verschiebungen werden auf den wirksamen Indent und MarginLeft des aktuellen Absatzes angewendet (die Ergebniswerte werden zu lokalen Werten). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual char16_t [get_Char](./get_char/)() | Gibt das Aufzählungszeichen-Zeichen eines Absatzes ohne Vererbung zurück. Lesen **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | Gibt das Farbformat eines Aufzählungszeichens eines Absatzes ohne Vererbung zurück. Nur Lesezugriff [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | Gibt die Aufzählungszeichen-Schriftart eines Absatzes ohne Vererbung zurück. Lesen [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | Gibt die Aufzählungszeichen-Höhe eines Absatzes ohne Vererbung zurück. Der Wert std::numeric_limits<float>::quiet_NaN() bestimmt, dass das Aufzählungszeichen die Höhe vom ersten Abschnitt im Absatz erbt. Lesen **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | Bestimmt, ob das Aufzählungszeichen eine eigene Farbe hat oder diese vom ersten Abschnitt im Absatz erbt. **[NullableBool::True](../nullablebool/)** wenn das Aufzählungszeichen eine eigene Farbe hat und **[NullableBool::False](../nullablebool/)** wenn das Aufzählungszeichen die Farbe vom ersten Abschnitt im Absatz erbt. Lesen [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | Bestimmt, ob das Aufzählungszeichen eine eigene Schriftart hat oder diese vom ersten Abschnitt im Absatz erbt. **[NullableBool::True](../nullablebool/)** wenn das Aufzählungszeichen eine eigene Schriftart hat und **[NullableBool::False](../nullablebool/)** wenn das Aufzählungszeichen die Schriftart vom ersten Abschnitt im Absatz erbt. Lesen [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | Gibt die erste Zahl zurück, die für eine Gruppe nummerierter Aufzählungszeichen ohne Vererbung verwendet wird. Lesen **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | Gibt den Stil eines nummerierten Aufzählungszeichens ohne Vererbung zurück. Lesen [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Gibt das Bild zurück, das als Aufzählungszeichen in einem Absatz ohne Vererbung verwendet wird. Nur Lesezugriff [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | Gibt den Aufzählungszeichen-Typ eines Absatzes ohne Vererbung zurück. Lesen [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | Erhält die wirklichen Aufzählungszeichen-Formatierungsdaten mit angewandter Vererbung. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht den Werttyp-Objektreferenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_Char](./set_char/)(char16_t) | Setzt das Aufzählungszeichen-Zeichen eines Absatzes ohne Vererbung. Schreiben **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Setzt die Aufzählungszeichen-Schriftart eines Absatzes ohne Vererbung. Schreiben [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | Setzt die Aufzählungszeichen-Höhe eines Absatzes ohne Vererbung. Der Wert std::numeric_limits<float>::quiet_NaN() bestimmt, dass das Aufzählungszeichen die Höhe vom ersten Abschnitt im Absatz erbt. Schreiben **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | Bestimmt, ob das Aufzählungszeichen eine eigene Farbe hat oder diese vom ersten Abschnitt im Absatz erbt. **[NullableBool::True](../nullablebool/)** wenn das Aufzählungszeichen eine eigene Farbe hat und **[NullableBool::False](../nullablebool/)** wenn das Aufzählungszeichen die Farbe vom ersten Abschnitt im Absatz erbt. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | Bestimmt, ob das Aufzählungszeichen eine eigene Schriftart hat oder diese vom ersten Abschnitt im Absatz erbt. **[NullableBool::True](../nullablebool/)** wenn das Aufzählungszeichen eine eigene Schriftart hat und **[NullableBool::False](../nullablebool/)** wenn das Aufzählungszeichen die Schriftart vom ersten Abschnitt im Absatz erbt. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | Setzt die erste Zahl, die für eine Gruppe nummerierter Aufzählungszeichen ohne Vererbung verwendet wird. Schreiben **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | Setzt den Stil eines nummerierten Aufzählungszeichens ohne Vererbung. Schreiben [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | Setzt den Aufzählungszeichen-Typ eines Absatzes ohne Vererbung. Schreiben [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert die Entsperrung des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)