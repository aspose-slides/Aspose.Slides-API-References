---
title: GetName()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Namen der Aufzählungskonstanten zurück, die den angegebenen Wert hat.
type: docs
weight: 40
url: /de/system/enum/getname/
---
## Enum::GetName(T) Methode

Gibt den Namen der Enumeration-Konstanten zurück, die den angegebenen Wert hat.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T | Der Wert der Aufzählungskonstante, deren Name zurückgegeben werden soll |

### Rückgabewert

Der Name der angegebenen Aufzählungskonstanten

## Siehe auch

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)