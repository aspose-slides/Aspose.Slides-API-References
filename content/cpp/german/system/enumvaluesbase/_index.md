---
title: EnumValuesBase
second_title: Aspose.Slides für C++ API-Referenz
description: Eine Basisklasse für eine Klasse, die Meta-Informationen eines Aufzählungstyps darstellt.
type: docs
weight: 807
url: /de/system/enumvaluesbase/
---
## EnumValuesBase Klasse

Eine Basisklasse für eine Klasse, die Meta-Informationen eines Aufzählungstyps darstellt.

```cpp
class EnumValuesBase
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Ruft ein Array der Namen der Konstanten einer angegebenen Aufzählung ab. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Gibt den zugrunde liegenden Typ der angegebenen Aufzählung zurück. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Gibt ein Array zurück, das alle Werte des angegebenen Aufzählungstyps enthält. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Gibt ein Objekt zurück, das einen Wert einer Aufzählungskonstanten des angegebenen Aufzählungstyps mit dem angegebenen Namen darstellt. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Konvertiert den angegebenen 64-Bit-Unsigned-Integer-Wert in ein Aufzählungsmitglied. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Konvertiert das angegebene Objekt mit einem Integer-Wert in ein Aufzählungsmitglied. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)