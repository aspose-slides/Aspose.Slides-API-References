---
title: Details_Exception
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt eine Ausnahme dar. Erstellen Sie niemals manuell Instanzen dieser Klasse. Verwenden Sie stattdessen die Exception-Klasse. Verpacken Sie die Exception-Klasseninstanzen niemals in System::SmartPtr."
type: docs
weight: 417
url: /de/system/details_exception/
---
## Details_Exception Klasse

Stellt eine Ausnahme dar. Erstellen Sie niemals manuell Instanzen dieser Klasse. Verwenden Sie stattdessen die Exception Klasse. Verpacken Sie die Exception Klasseninstanzen niemals in [System::SmartPtr](../smartptr/).

```cpp
class Details_Exception : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [DoThrow](./dothrow/)(const [ExceptionPtr](../exceptionptr/)\&) const | Wirft die von einem Ausnahme-Wrapper umschlossene Ausnahminstanz. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](./get_data/)() | Gibt ein Wörterbuch mit benutzerdefinierten Ausnahmedaten zurück. |
| **int32_t** [get_HResult](./get_hresult/)() const | Gibt einen 32-Bit-Ganzzahlwert zurück, der ein HRESULT-Code ist, der der von dem aktuellen Objekt repräsentierten Ausnahme zugeordnet ist. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [get_InnerException](./get_innerexception/)() const | Gibt eine Referenz auf das Objekt zurück, das die innere Ausnahme darstellt. |
| virtual [String](../string/) [get_Message](./get_message/)() const | Gibt die Zeichenkette zurück, die die Fehlermeldung enthält. |
| virtual [String](../string/) [get_StackTrace](./get_stacktrace/)() const | Gibt die Zeichenkette zurück, die den Stack-Trace enthält. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [GetBaseException](./getbaseexception/)() const | Gibt eine Kopie des Exception-Objekts zurück, das die innerste Ausnahme repräsentiert. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../object/gettype/)-Aufruf. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../object/lock/)() | Implementiert das Sperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../lockcontext/)-Sentry-Objekt verwenden. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy-Konstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| void [set_HResult](./set_hresult/)(**int32_t**) | Setzt HRESULT, einen codierten numerischen Wert, der einer bestimmten Ausnahme zugeordnet ist. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsam genutzten Referenzzählers. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Erhöht die gemeinsam genutzte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsam genutzte Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| [String](../string/) [ToString](./tostring/)() const override | Gibt die String-Repräsentation des aktuellen Objekts zurück. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementiert das C#-typeof([System.Object](../object/))-Konstrukt. |
| void [Unlock](../object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../lockcontext/)-Sentry-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| virtual const char * [what](./what/)() const | Implementiert die [what()](./what/)-Methode, die von der [ExceptionWrapper](../exceptionwrapper/)-Klasse aufgerufen wird. Trotz der Tatsache, dass diese Klasse nicht von std::exception erbt, können abgeleitete Klassen geschützte/ private Mitglieder verwenden, um ihre Logik zu implementieren. Das Verschieben dieser Methodenimplementierung in das [ExceptionWrapper](../exceptionwrapper/) könnte diese Logik brechen. |
| virtual  [~Object](../object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../object/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)