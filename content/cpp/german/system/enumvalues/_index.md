---
title: EnumValues
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Meta-Informationen über Aufzählungskonstanten des Aufzählungstyps E bereit.
type: docs
weight: 794
url: /de/system/enumvalues/
---
## EnumValues Klasse

Stellt Meta-Informationen über Aufzählungskonstanten des Aufzählungstyps **E** bereit.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| E | Der Typ der Aufzählung |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Konstruiert eine Instanz. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Gibt ein Array zurück, das alle Namen der Aufzählung **E** enthält. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Ruft ein Array der Namen der Konstanten einer angegebenen Aufzählung ab. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Gibt den zugrunde liegenden Typ der angegebenen Aufzählung zurück. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Gibt den zugrunde liegenden Typ der angegebenen Aufzählung zurück. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Gibt den verpackten Wert der Enum-Konstanten mit dem angegebenen Namen zurück. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Gibt den verpackten Wert der Enum-Konstanten mit dem angegebenen Wert zurück. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Gibt ein Array zurück, das alle Werte der Aufzählung **E** enthält. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Gibt ein Array zurück, das alle Werte des angegebenen Aufzählungstyps enthält. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Gibt ein Objekt zurück, das einen Wert einer Enum-Konstanten des angegebenen Aufzählungstyps mit dem angegebenen Namen darstellt. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Konvertiert den angegebenen 64-Bit-Unsigned-Integer-Wert in ein Aufzählungsmitglied. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Konvertiert das angegebene Objekt mit einem Integer-Wert in ein Aufzählungsmitglied. |
| virtual  [~EnumValues](./~enumvalues/)() | Destruktor. |

## Siehe auch

* Klasse [EnumValuesBase](../enumvaluesbase/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)