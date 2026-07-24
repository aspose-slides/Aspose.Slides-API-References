---
title: FieldType
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Feldtyp dar. Dieser Wert bestimmt, welcher Text dem Feldabschnitt zugewiesen wird, wenn er aktualisiert wird.
type: docs
weight: 872
url: /de/aspose.slides/fieldtype/
---
## FieldType Klasse

Stellt einen Feldtyp dar. Dieser Wert bestimmt, welcher Text dem Feldabschnitt zugewiesen wird, wenn er aktualisiert wird.

```cpp
class FieldType : public Aspose::Slides::IFieldType
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Prüft, ob dieses Feld einem anderen gleich ist. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur zu internen Zwecken. |
|  [FieldType](./fieldtype/)([System::String](../../system/string/)) | Initialisiert eine neue Instanz der [FieldType](./) Klasse. |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime](./get_datetime/)() | Aktuelles Datum und Uhrzeit im Standard-Datumszeitformat für die Rendering-Anwendung. Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime1](./get_datetime1/)() | Aktuelles Datum und Uhrzeit in einem ersten vordefinierten Format (MM/DD/YYYY für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime10](./get_datetime10/)() | Aktuelles Datum und Uhrzeit in einem zehnten vordefinierten Format (hh:mm für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime11](./get_datetime11/)() | Aktuelles Datum und Uhrzeit in einem elften vordefinierten Format (hh:mm:ss für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime12](./get_datetime12/)() | Aktuelles Datum und Uhrzeit in einem zwölften vordefinierten Format (hh:mm AM/PM für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime13](./get_datetime13/)() | Aktuelles Datum und Uhrzeit in einem dreizehnten vordefinierten Format (hh:mm:ss AM/PM für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime2](./get_datetime2/)() | Aktuelles Datum und Uhrzeit in einem zweiten vordefinierten Format (Day, Month DD, YYYY für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime3](./get_datetime3/)() | Aktuelles Datum und Uhrzeit in einem dritten vordefinierten Format (DD Month YYYY für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime4](./get_datetime4/)() | Aktuelles Datum und Uhrzeit in einem vierten vordefinierten Format (Month DD, YYYY für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime5](./get_datetime5/)() | Aktuelles Datum und Uhrzeit in einem fünften vordefinierten Format (DD-Mon-YY für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime6](./get_datetime6/)() | Aktuelles Datum und Uhrzeit in einem sechsten vordefinierten Format (Month YY für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime7](./get_datetime7/)() | Aktuelles Datum und Uhrzeit in einem siebten vordefinierten Format (Mon-YY für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime8](./get_datetime8/)() | Aktuelles Datum und Uhrzeit in einem achten vordefinierten Format (MM/DD/YYYY hh:mm AM/PM für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime9](./get_datetime9/)() | Aktuelles Datum und Uhrzeit in einem neunten vordefinierten Format (MM/DD/YYYY hh:mm:ss AM/PM für Englisch). Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Footer](./get_footer/)() | [Slide](../slide/)'s Fußzeile. Nur lesbar [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Header](./get_header/)() | [Slide](../slide/)'s Kopfzeile. Nur lesbar [FieldType](./). |
| [System::String](../../system/string/) [get_InternalString](./get_internalstring/)() override | Gibt den internen Namen dieses [FieldType](./) Objekts zurück. Lies [System::String](../../system/string/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_SlideNumber](./get_slidenumber/)() | Aktuelle Foliennummer. Nur lesbar [FieldType](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die mit dem Objekt verknüpft ist. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für dieses Objekt zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das C# lock()-Statement für die Sperrung. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenzvergleicht Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| void [set_InternalString](./set_internalstring/)([System::String](../../system/string/)) override | Gibt den internen Namen dieses [FieldType](./) Objekts zurück. Schreiben [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C# lock()-Statement zum Entsperren. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IFieldType](../ifieldtype/)
* Namensraum [Aspose::Slides](../)
* Library [Aspose.Slides](../../)