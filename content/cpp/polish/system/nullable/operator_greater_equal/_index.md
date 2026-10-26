---
title: operator>=()
second_title: Aspose.Slides dla C++ Odniesienie API
description: Zawsze zwraca false.
type: docs
weight: 183
url: /pl/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const metoda


Zawsze zwraca false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Wartość zwracana

Zawsze - false

## Nullable::operator>=(const T1\&) const metoda


Określa, czy wartość reprezentowana przez bieżący obiekt jest większa lub równa wartości reprezentowanej przez określony obiekt, stosując [operator>=()](./) do tych wartości.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T1 | Typ bazowy wartości, z którą porównywana jest wartość reprezentowana przez bieżący obiekt |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Stała referencja do obiektu, z którym porównywany jest bieżący obiekt |

### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt jest większa lub równa wartości reprezentowanej przez określony obiekt, w przeciwnym razie - false

## Nullable::operator>=(const Nullable\<T1\>\&) const metoda


Określa, czy wartość reprezentowana przez bieżący obiekt jest większa lub równa wartości reprezentowanej przez określony obiekt [Nullable](../), stosując [operator>=()](./) do tych wartości.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T1 | Typ bazowy obiektu [Nullable](../), z którym porównywana jest wartość |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Stała referencja do obiektu [Nullable](../), z którym porównywany jest bieżący obiekt |

### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt jest większa lub równa wartości reprezentowanej przez określony obiekt [Nullable](../), w przeciwnym razie - false

## Zobacz także

* Klasa [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)