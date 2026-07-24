---
title: operator[]()
second_title: Aspose.Slides für C++ API-Referenz
description: Zugriffsoperator zur Arbeit mit Schlüsseltypumwandlung.
type: docs
weight: 14
url: /de/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const X\&) const Methode

Zugriffsoperator zur Arbeit mit Schlüsseltypumwandlung.

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| X | Quellschlüsseltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) Schlüssel. |

### Rückgabewert

Referenz auf den Wert, der dem übergebenen Schlüssel entspricht, bereits vorhanden oder neu erstellt.

## DictionaryPtr::operator[](const T\&) const Methode

Zugriffsoperator.

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) Schlüssel. |

### Rückgabewert

Referenz auf den Wert, der dem übergebenen Schlüssel entspricht, bereits vorhanden oder neu erstellt.

## Siehe auch

* Klasse [DictionaryPtr](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)