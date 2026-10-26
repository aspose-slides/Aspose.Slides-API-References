---
title: BoxedValueBase
second_title: "Aspose.Slides für C++ API-Referenz"
description: "Eine Basisklasse, die ein Interface definiert und einige grundlegende Methoden einer abgeleiteten Klasse implementiert, die einen verpackten Wert darstellt. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu uebergeben."
type: docs
weight: 131
url: /de/system/boxedvaluebase/
---
## BoxedValueBase Klasse


Eine Basisklasse, die ein Interface definiert und einige grundlegende Methoden einer abgeleiteten Klasse implementiert, die einen verpackten Wert darstellt. Objekte dieser Klasse sollten nur mittels der Funktion [System::MakeObject()](../makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class BoxedValueBase : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Entspricht der C#-Methode [Object.GetHashCode()](../object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Entspricht dem C#-Aufruf [System.Object.GetType()](../object/gettype/). |
| virtual [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Gibt den Wert zurück, der den Typ des verpackten Wertes des aktuellen Objekts darstellt. |
| virtual **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const | Konvertiert das vom aktuellen Objekt dargestellte verpackte Objekt in einen 64-Bit-Ganzzahlwert. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Entspricht dem C#-Operator 'is'. |
| virtual **bool** [IsBoxedEnum](./isboxedenum/)() | Bestimmt, ob das aktuelle Objekt einen verpackten Wert eines Aufzählungstyps darstellt. |
| void [Lock](../object/lock/)() | Implementiert das Sperren der C#-Anweisung lock(). Rufen Sie es direkt auf oder verwenden Sie das [LockContext](../lockcontext/)-Wächterobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Entspricht der C#-Methode [Object.MemberwiseClone()](../object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Verpackt den Wert einer Aufzählungskonstanten der angegebenen Aufzählung mit dem angegebenen Namen. Ein Parameter gibt an, ob die Groß-/Kleinschreibung beim Interpretieren des Strings, der den Namen der Aufzählungskonstanten angibt, ignoriert werden soll. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Verpackt den Wert einer Aufzählungskonstanten der angegebenen Aufzählung mit dem angegebenen Namen. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| [System::String](../string/) [ToString](./tostring/)(const [System::String](../string/)\&) const | Konvertiert das verpackte Objekt in eine Zeichenkette mittels des angegebenen Format-Strings. |
| virtual [String](../string/) [ToString](./tostring/)() const | Entspricht der C#-Methode [Object.ToString()](../object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementiert das Entsperren der C#-Anweisung lock(). Rufen Sie es direkt auf oder verwenden Sie das [LockContext](../lockcontext/)-Wächterobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual  [~Object](../object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../object/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)