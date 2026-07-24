---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Objekt zurück, das einen Wert einer Aufzählungskonstante des angegebenen Aufzählungstyps mit dem angegebenen Namen darstellt.
type: docs
weight: 27
url: /de/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) Methode

Gibt ein Objekt zurück, das einen Wert einer Aufzählungskonstante des angegebenen Aufzählungstyps mit dem angegebenen Namen darstellt.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Das [TypeInfo](../../typeinfo/) Objekt, das den Typ des zurückzugebenden Aufzählungswerts darstellt |
| str | const [String](../../string/)\& | Der Name der Aufzählungskonstante |
| ignoreCase | **bool** | Gibt an, ob die Groß-/Kleinschreibung bei der Interpretation des Namens der Aufzählungskonstante ignoriert werden soll |

### Rückgabewert

Ein Objekt, das den Wert der Aufzählungskonstante darstellt, deren Name in **str** angegeben ist.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [TypeInfo](../../typeinfo/)
* Klasse [String](../../string/)
* Klasse [EnumValuesBase](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)