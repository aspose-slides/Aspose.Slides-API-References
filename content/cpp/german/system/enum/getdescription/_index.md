---
title: GetDescription()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Namen der Aufzählungskonstante zurück, die den angegebenen Wert hat.
type: docs
weight: 53
url: /de/system/enum/getdescription/
---
## Enum::GetDescription(T) Methode

Gibt den Namen der Aufzählungskonstante zurück, die den angegebenen Wert hat.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T | Der Wert der Aufzählungskonstante, deren Name zurückgegeben werden soll |

### Rückgabewert

Der Name der angegebenen Aufzählungskonstante

## Siehe auch

* Typedef [UnderlyingType](../underlyingtype/)
* Klasse [String](../../string/)
* Struktur [Enum](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)