---
title: TextInfo
second_title: Aspose.Slides für C++ API-Referenz
description: "Definiert lokalspezifische Texteigenschaften. Setter-Operationen sind nur bei nicht schreibgeschützten Objekten aktiviert. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 365
url: /de/system.globalization/textinfo/
---
## TextInfo Klasse


Definiert lokalspezifische Texteigenschaften. Setter-Operationen sind nur bei nicht schreibgeschützten Objekten aktiviert. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class TextInfo : public System::ICloneable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Erstellt eine Kopie des aktuellen Objekts und gibt einen Shared-Pointer darauf zurück. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Fließkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Fließkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual int [get_ANSICodePage](./get_ansicodepage/)() const | Gibt die ANSI-Codepage zurück. |
| [String](../../system/string/) [get_CultureName](./get_culturename/)() const | Gibt den Kulturnamen zurück. |
| virtual int [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | Gibt die EBCDIC-Codepage zurück. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Prüft, ob das Format schreibgeschützt ist. |
| **bool** [get_IsRightToLeft](./get_isrighttoleft/)() const | Prüft, ob der Text von links nach rechts geschrieben wird. |
| int [get_LCID](./get_lcid/)() const | Gibt die Locale-ID zurück. |
| virtual [String](../../system/string/) [get_ListSeparator](./get_listseparator/)() const | Gibt das Listentrennzeichen zurück. |
| virtual int [get_MacCodePage](./get_maccodepage/)() const | Gibt die Macintosh-Codepage zurück. |
| virtual int [get_OEMCodePage](./get_oemcodepage/)() const | Gibt die OEM-Codepage zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die mit dem Objekt verknüpft ist. |
| int [GetHashCode](./gethashcode/)() const override | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [TextInfo](./)\& [operator=](./operator_equal/)(const [TextInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static [TextInfoPtr](../textinfoptr/) [ReadOnly](./readonly/)(const [TextInfoPtr](../textinfoptr/)\&) | Gibt eine schreibgeschützte Version der Kultur zurück. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_ListSeparator](./set_listseparator/)([String](../../system/string/)) | Setzt das Listentrennzeichen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| [TextInfo](./textinfo/)(const [TextInfo](./)\&) | RTTI-Information. |
| virtual char_t [ToLower](./tolower/)(char_t) const | Konvertiert ein Zeichen in Kleinbuchstaben. |
| virtual [String](../../system/string/) [ToLower](./tolower/)([String](../../system/string/)) const | Konvertiert einen String in Kleinbuchstaben. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| [String](../../system/string/) [ToTitleCase](./totitlecase/)([String](../../system/string/)) const | Konvertiert einen String in die Title-Case (außer für Akronyme, die bereits in Großbuchstaben vorliegen). |
| virtual char_t [ToUpper](./toupper/)(char_t) const | Konvertiert ein Zeichen in Großbuchstaben. |
| virtual [String](../../system/string/) [ToUpper](./toupper/)([String](../../system/string/)) const | Konvertiert einen String in Großbuchstaben. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Ausdruck. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [ICloneable](../../system/icloneable/)
* Namensraum [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)