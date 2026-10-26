---
title: GetValueOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den geboxten Wert der Enum-Konstanten mit dem angegebenen Namen zurück.
type: docs
weight: 53
url: /de/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const Methode

Gibt den geboxten Wert der Enum-Konstanten mit dem angegebenen Namen zurück.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../string/)\& | Der Name der Enum-Konstanten |
| ignoreCase | **bool** | Gibt an, ob die Groß-/Kleinschreibung beim Interpretieren des Namens der Enum-Konstanten ignoriert werden soll |

### Rückgabewert

Ein geboxter Wert der Enum-Konstanten, deren Name in **str** angegeben ist.

## EnumValues::GetValueOf(long) const Methode

Gibt den geboxten Wert der Enum-Konstanten mit dem angegebenen Wert zurück.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| val | long | Der Wert der Enum-Konstanten |

### Rückgabewert

Ein geboxter Wert der Enum-Konstanten, deren vakye in **str** angegeben ist.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [String](../../string/)
* Klasse [EnumValues](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)