---
title: IsDefined()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob der angegebene Wert ein Mitglied des Aufzählungstyps E ist.
type: docs
weight: 27
url: /de/system/enum/isdefined/
---
## Enum::IsDefined(E) Methode


Bestimmt, ob der angegebene Wert ein Mitglied des Aufzählungstyps **E** ist.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | E | Der zu prüfende Wert |

### Rückgabewert

True, wenn **value** ein Mitglied der Aufzählung **E** ist, sonst - false

## Enum::IsDefined(T) Methode


Bestimmt, ob der angegebene Wert ein Mitglied des Aufzählungstyps **T** ist.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T | Der zu prüfende Wert |

### Rückgabewert

True, wenn **value** ein Mitglied der Aufzählung **T** ist, sonst - false

## Enum::IsDefined(const String\&) Methode


Bestimmt, ob der Wert mit dem angegebenen Namen zu den Mitgliedern des Enums **E** gehört.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../string/)\& | Der zu prüfende Name |

### Rückgabewert

True, wenn ein Mitglied des Enums **E** mit dem angegebenen Namen existiert.

## Siehe auch

* Typedef [UnderlyingType](../underlyingtype/)
* Klasse [String](../../string/)
* Struct [Enum](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)