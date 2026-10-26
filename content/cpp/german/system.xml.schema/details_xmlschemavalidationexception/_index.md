---
title: Details_XmlSchemaValidationException
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Ausnahme dar, die ausgelöst wird, wenn bei der Validierung eines XML-Dokuments XML Schema Definition Language (XSD) Schema-Validierungsfehler und -Warnungen auftreten.
type: docs
weight: 27
url: /de/system.xml.schema/details_xmlschemavalidationexception/
---
## Details_XmlSchemaValidationException Klasse

Stellt die Ausnahme dar, die ausgelöst wird, wenn XML [Schema](../) Definition Language (XSD) Schema-Validierungsfehler und -Warnungen in einem zu validierenden XML-Dokument auftreten.

```cpp
class Details_XmlSchemaValidationException : public System::Xml::Schema::Details_XmlSchemaException
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschliesslich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschliesslich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur fuer interne Zwecke. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Gibt ein Woerterbuch mit benutzerdefinierten Ausnahmedaten zurueck. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Gibt einen 32-Bit-Ganzzahlwert zurueck, der ein HRESULT-Code ist, der der vom aktuellen Objekt dargestellten Ausnahme zugeordnet ist. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Gibt eine Referenz auf das Objekt zurueck, das die innere Ausnahme darstellt. |
| **int32_t** [get_LineNumber](../details_xmlschemaexception/get_linenumber/)() | Gibt die Zeilennummer zurueck, die angibt, wo der Fehler aufgetreten ist. |
| **int32_t** [get_LinePosition](../details_xmlschemaexception/get_lineposition/)() | Gibt die Zeilenposition zurueck, die angibt, wo der Fehler aufgetreten ist. |
| [String](../../system/string/) [get_Message](../details_xmlschemaexception/get_message/)() const override | Gibt die Beschreibung des Fehlerzustands dieser Ausnahme zurueck. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SourceObject](./get_sourceobject/)() | Gibt den XML-Knoten zurueck, der diese XmlSchemaValidationException verursacht hat. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_SourceSchemaObject](../details_xmlschemaexception/get_sourceschemaobject/)() | Das **[XmlSchemaObject](../xmlschemaobject/)**, das die XmlSchemaException erzeugt hat. |
| [String](../../system/string/) [get_SourceUri](../details_xmlschemaexception/get_sourceuri/)() | Gibt den Uniform Resource Identifier (URI) des Schemas zurueck, das die Ausnahme verursacht hat. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Gibt die Zeichenkette zurueck, die den Stack-Trace enthaelt. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Gibt eine Kopie des Exception-Objekts zurueck, das die innere Ausnahme darstellt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzaehler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C#-lock()-Statements. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert tatsächlich nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) fuer den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) fuer den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzaehler um den angegebenen Wert. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Setzt HRESULT, einen kodierten numerischen Wert, der einer bestimmten Ausnahme zugeordnet wird. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzaehlers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhoeht den gemeinsamen Referenzzaehler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzaehler zurueck. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Gibt die Zeichenkettenrepräsentation des aktuellen Objekts zurueck. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhoeht den Weak-Referenzzaehler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzaehler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementiert die Methode [what()](../../system/details_exception/what/), die von der Klasse [ExceptionWrapper](../../system/exceptionwrapper/) aufgerufen wird. Trotz der Tatsache, dass diese Klasse nicht von std::exception erbt, können abgeleitete Klassen geschützte/private Mitglieder verwenden, um ihre Logik zu implementieren. Das Verschieben dieser Methodenumsetzung in das [ExceptionWrapper](../../system/exceptionwrapper/) könnte diese Logik brechen. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias fuer einen Shared-Pointer auf eine Instanz dieser Klasse. |

## Siehe auch

* Klasse [Details_XmlSchemaException](../details_xmlschemaexception/)
* Namensraum [System::Xml::Schema](../)
* Bibliothek [Aspose.Slides](../../)