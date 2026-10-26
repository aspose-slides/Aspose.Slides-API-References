---
title: operator<=()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zawsze zwraca false.
type: docs
weight: 196
url: /pl/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const metoda

Zawsze zwraca false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const metoda

Określa, czy wartość reprezentowana przez bieżący obiekt jest mniejsza lub równa określonej wartości poprzez zastosowanie [operator<=()](./) do tych wartości.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ wartości do porównania |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const T1\& | Stały referencyjny do wartości do porównania |

### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt jest mniejsza lub równa określonej wartości, w przeciwnym razie - false

## Nullable::operator<=(const Nullable\<T1\>\&) const metoda

Określa, czy wartość reprezentowana przez bieżący obiekt jest mniejsza lub równa wartości reprezentowanej przez określony obiekt [Nullable](../) poprzez zastosowanie [operator<=()](./) do tych wartości.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Podstawowy typ obiektu [Nullable](../) do porównania |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Stały referencyjny do obiektu [Nullable](../) do porównania |

### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt jest mniejsza lub równa wartości reprezentowanej przez określony obiekt [Nullable](../), w przeciwnym razie - false

## Zobacz także

* Klasa [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)