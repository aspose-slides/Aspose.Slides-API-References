---
title: Equals()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy wartość reprezentowana przez bieżący obiekt jest równa wartości reprezentowanej przez określony obiekt Nullable.
type: docs
weight: 131
url: /pl/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const metoda


Określa, czy wartość reprezentowana przez bieżący obiekt jest równa wartości reprezentowanej przez określony obiekt [Nullable](../).

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const T1\& | A constant reference to the [Nullable](../) object to compare with |

### Wartość zwracana

Prawda, jeśli wartość reprezentowana przez bieżący obiekt jest równa wartości reprezentowanej przez określony obiekt [Nullable](../), w przeciwnym razie - fałsz

## Zobacz także

* Klasa [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)