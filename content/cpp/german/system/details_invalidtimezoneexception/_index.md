---
title: Details_InvalidTimeZoneException
second_title: Aspose.Slides für C++ API-Referenz
description: "InvalidTimeZoneException wird ausgelöst, wenn Zeitzoneninformationen ungültig sind. Erstellen Sie niemals manuell Instanzen dieser Klasse. Verwenden Sie stattdessen die InvalidTimeZoneException Klasse. Wickeln Sie die InvalidTimeZoneException Klasseninstanzen niemals in System::SmartPtr ein."
type: docs
weight: 534
url: /de/system/details_invalidtimezoneexception/
---
## Details_InvalidTimeZoneException Klasse

InvalidTimeZoneException wird ausgelöst, wenn Zeitzoneninformationen ungültig sind. Erstellen Sie niemals manuell Instanzen dieser Klasse. Verwenden Sie stattdessen die InvalidTimeZoneException Klasse. Wickeln Sie die InvalidTimeZoneException Klasseninstanzen niemals in [System::SmartPtr](../smartptr/) ein.

```cpp
class Details_InvalidTimeZoneException : public System::Details_Exception
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergleicht Objekte mithilfe von C# [Object.Equals](../object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Gibt ein Wörterbuch mit benutzerdefinierten Ausnahmedaten zurück. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Gibt einen 32-Bit-Integer-Wert zurück, der ein HRESULT-Code ist, der mit der vom aktuellen Objekt repräsentierten Ausnahme verknüpft ist. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Gibt eine Referenz auf das Objekt zurück, das die innere Ausnahme darstellt. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Gibt die Zeichenkette zurück, die die Fehlermeldung enthält. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Gibt die Zeichenkette zurück, die den Stack-Trace enthält. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Gibt eine Kopie des Exception-Objekts zurück, das die innerste Ausnahme darstellt. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../object/gettype/)-Aufruf. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verringert den gemeinsam genutzten Referenzzähler um den angegebenen Wert. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Setzt HRESULT, einen codierten Zahlenwert, der einer bestimmten Ausnahme zugewiesen wird. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsam genutzten Referenzzählers. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Erhöht den gemeinsam genutzten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsam genutzten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Gibt die Zeichenkettenrepräsentation des aktuellen Objekts zurück. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual const char * [what](../details_exception/what/)() const | Implementiert die [what()](../details_exception/what/)-Methode, die von der [ExceptionWrapper](../exceptionwrapper/) Klasse aufgerufen wird. Trotz der Tatsache, dass diese Klasse nicht von std::exception erbt, können von ihr abgeleitete Klassen geschützte/private Member verwenden, um ihre Logik zu implementieren. Das Verschieben dieser Methodenumsetzung in den [ExceptionWrapper](../exceptionwrapper/) könnte diese Logik brechen. |
| virtual  [~Object](../object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Details_Exception](../details_exception/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)