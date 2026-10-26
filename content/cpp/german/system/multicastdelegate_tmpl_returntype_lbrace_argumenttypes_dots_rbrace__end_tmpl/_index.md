---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt eine Sammlung von Delegaten dar. Dieser Typ sollte auf dem Stack allokiert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 1093
url: /de/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> Klasse


Stellt eine Sammlung von Delegaten dar. Dieser Typ sollte auf dem Stack allokiert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ReturnType | Rückgabetyp der aufrufbaren Entitäten, auf die jeder Delegat in der Sammlung zeigt |
| ArgumentTypes | Argumentliste der aufrufbaren Entitäten, auf die jeder Delegat in der Sammlung zeigt |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NOT IMPLEMENTED. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Fügt den angegebenen Delegaten zur Sammlung hinzu. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Fügt das angegebene Funktionsobjekt zur Delegatensammlung hinzu. Das Funktionsobjekt wird vor dem Hinzufügen in den Callback-Delegaten-Typ konvertiert. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Fügt das angegebene MulticastDelegate-Objekt zur Delegatensammlung hinzu. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Fügt die angegebene nicht-statische Methode des angegebenen Objekts zur Delegatensammlung hinzu. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Fügt die angegebene nicht-statische Methode des angegebenen Objekts zur Delegatensammlung hinzu. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Entfernt den angegebenen Delegaten aus der Delegatensammlung. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Entfernt die angegebene nicht-statische Methode des angegebenen Objekts aus der Delegatensammlung. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Entfernt die angegebene nicht-statische Methode des angegebenen Objekts aus der Delegatensammlung. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Entfernt das angegebene MulticastDelegate-Objekt aus der Delegatensammlung. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Entfernt alle Delegaten aus der Delegatensammlung. |
| **bool** [empty](./empty/)() const | Bestimmt, ob die Delegatensammlung leer ist. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NOT IMPLEMENTED. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Ruft alle derzeit in der Delegatensammlung vorhandenen Delegaten auf. Delegaten werden in derselben Reihenfolge aufgerufen, in der sie zur Sammlung hinzugefügt wurden. Die Methode blockiert, solange die Delegaten ausgeführt werden. |
| **bool** [IsNull](./isnull/)() const | Bestimmt, ob die Delegatensammlung leer ist. |
|  [MulticastDelegate](./multicastdelegate/)() | Konstruiert eine leere Sammlung. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Entspricht dem Standardkonstruktor. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Führt eine flache Kopie der Delegatensammlung durch. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Move-Konstruktor. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Konstruiert eine Instanz und fügt den angegebenen Delegaten zur Delegatensammlung hinzu. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Konstruiert eine Instanz und fügt den angegebenen Wert zur Delegatensammlung hinzu. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Konstruiert eine Instanz und fügt den angegebenen Wert zur Delegatensammlung hinzu. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Bestimmt, ob die Delegatensammlung nicht leer ist. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Bestimmt, ob zwei Instanzen von MulticastDelegate – das aktuelle Objekt und das angegebene Objekt – ungleich sind. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Ruft alle derzeit in der Delegatensammlung vorhandenen Delegaten auf. Delegaten werden in derselben Reihenfolge aufgerufen, in der sie zur Sammlung hinzugefügt wurden. Der Operator blockiert, solange die Delegaten ausgeführt werden. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Fügt den angegebenen Delegaten zur Sammlung hinzu. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Entfernt den angegebenen Delegaten aus der Delegatensammlung. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Weist die durch das angegebene Objekt dargestellte Delegatensammlung dem aktuellen Objekt zu. Beide Objekte verweisen anschließend auf dieselbe Delegatensammlung. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Move-Zuweisungsoperator. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Bestimmt, ob die Delegatensammlung leer ist. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Bestimmt, ob zwei Instanzen von MulticastDelegate – das aktuelle Objekt und das angegebene Objekt – gleich sind. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Bereinigt enthaltene Callbacks, die leer sind (es wird nichts tatsächlich aufgerufen). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Gibt eine Referenz auf das [TypeInfo](../typeinfo/)-Objekt zurück, das die Typinformationen der MulticastDelegate-Klasse repräsentiert. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destruktor. |
## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [Callback](./callback/) | Der Typ der von der MulticastDelegate-Klasse repräsentierten Delegaten. |
| [Function](./function/) | Der Typ der Funktion, die zur Delegaten-Signatur gehört. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)