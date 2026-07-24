---
title: DefaultBoxedValue
second_title: Aspose.Slides für C++ API-Referenz
description: "BoxedValue-Klassenimplementierung. Ermöglicht, dass BoxingValue-Spezialisierungen deklariert werden können, ohne gemeinsamen Code zu duplizieren. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Kapseln Sie diese Klasse stets in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 274
url: /de/system/defaultboxedvalue/
---
## DefaultBoxedValue Klasse


[BoxedValue](../boxedvalue/) Klassenimplementierung. Ermöglicht es, BoxingValue-Spezialisierungen ohne Duplizieren von gemeinsamem Code zu deklarieren. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Kapseln Sie diese Klasse immer in einen [System::SmartPtr](../smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Konstruiert eine neue Instanz der Klasse [DefaultBoxedValue](./), die den angegebenen Wert repräsentiert. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Bestimmt die Gleichheit der verpackten Werte, die von den aktuellen und den angegebenen Objekten repräsentiert werden. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| int [GetHashCode](./gethashcode/)() const override | Gibt einen Hash-Code für das aktuelle Objekt zurück. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Liefert den tatsächlichen Typ des Objekts. |
| **bool** [is](./is/)() const | Bestimmt, ob der Typ des verpackten Wertes, der vom aktuellen Objekt repräsentiert wird, **V** ist. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentry-Objekt [LockContext](../lockcontext/) verwenden. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../object/object/)([Object](../object/) const\&) | Kopie-Konstruktor. Kopiert eigentlich nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Zuweisungsoperator. Kopiert eigentlich nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt einem geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [String](../string/) [ToString](./tostring/)() const override | Gibt die Zeichenkettenrepräsentation des verpackten Wertes zurück. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementiert den C#-typeof([System.Object](../object/))-Konstruktor. |
| const T\& [unbox](./unbox/)() const | Entpackt den verpackten Wert. |
| void [Unlock](../object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentry-Objekt [LockContext](../lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [~Object](../object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../object/)
* Namensraum [System](../)
* Library [Aspose.Slides](../../)