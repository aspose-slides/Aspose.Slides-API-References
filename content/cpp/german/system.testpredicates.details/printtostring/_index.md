---
title: PrintToString()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Objekt als Zeichenkette aus, indem die passende Serialisierungsfunktion ausgewählt wird.
type: docs
weight: 1
url: /de/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T&) Funktion

Gibt das Objekt als Zeichenkette aus, indem die passende Serialisierungsfunktion ausgewählt wird.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T& | [Object](../../system/object/) zum Drucken. |

### Rückgabewert

[String](../../system/string/) Darstellungen des übergebenen Objekts.

## System::TestPredicates::Details::PrintToString(const T&) Funktion

Gibt ICollection-artige Container als Zeichenkette aus, indem ihre Elemente (nicht mehr als 32) ausgegeben werden.

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T& | [Object](../../system/object/) zum Drucken. |

### Rückgabewert

Gemeinsame Zeichenkettenrepräsentationen der enthaltenen Elemente.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) Funktion

Gibt nullptr als Zeichenkette aus.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### Rückgabewert

"nullptr" Zeichenkette.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>&) Funktion

Gibt [IEnumerable<bool>](../../system.collections.generic/ienumerable/) Sammlungen als Zeichenkette aus, indem ihre Elemente (nicht mehr als 32) ausgegeben werden.

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)<**bool**>& | [Object](../../system/object/) zum Drucken. |

### Rückgabewert

Gemeinsame Zeichenkettenrepräsentationen der enthaltenen Elemente.

## Siehe auch

* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Struktur [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Namensraum [System::TestPredicates::Details](../)
* Bibliothek [Aspose.Slides](../../)