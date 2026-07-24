---
title: ValueTuple
second_title: Aspose.Slides für C++ API-Referenz
description: Klasse, die eine ValueTuple-Datenstruktur darstellt.
type: docs
weight: 1444
url: /de/system/valuetuple/
---
## ValueTuple Klasse

Klasse, die eine [ValueTuple](./) Datenstruktur darstellt.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Bestimmt, ob das aktuelle und das angegebene Objekt identisch sind. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Gibt die Referenz auf den Wert der Komponente des [ValueTuple](./)-Objekts zurück. |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Gibt den Wert der Komponente des [ValueTuple](./)-Objekts zurück. |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Zerlegt das Objekt in dieses Wert-Tuple. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Gibt eine Referenz auf das [TypeInfo](../typeinfo/)-Objekt zurück, das die Typinformationen der [ValueTuple](./) Klasse darstellt. |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Konstruiert ein Tuple-Objekt. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)