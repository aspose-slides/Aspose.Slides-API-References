---
title: MakeArray()
second_title: Aspose.Slides dla C++ – dokumentacja interfejsu API
description: Funkcja fabryczna, która tworzy nowy obiekt Array, wypełnia go elementami z podanej listy inicjalizacyjnej i zwraca inteligentny wskaźnik wskazujący na obiekt Array.
type: docs
weight: 2029
url: /pl/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) funkcja


Funkcja fabryczna, która tworzy nowy obiekt [Array](../array/), wypełnia go elementami z podanej listy inicjalizacyjnej i zwraca inteligentny wskaźnik wskazujący na obiekt [Array](../array/).

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów obiektu [Array](../array/) tworzonego przez funkcję |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| init | std::initializer_list\<T\> | Lista inicjalizacyjna zawierająca elementy, które mają zostać użyte do wypełnienia tablicy |

### Wartość zwracana

Inteligentny wskaźnik wskazujący na skonstruowany obiekt [Array](../array/)

## System::MakeArray(Args\&&...) funkcja


Funkcja fabryczna, która tworzy nowy obiekt [Array](../array/), przekazując określone argumenty do jego konstruktora.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów obiektu [Array](../array/) tworzonego przez funkcję |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | Args\&&... | Argumenty, które są przekazywane do konstruktora obiektu [Array](../array/) będącego w trakcie konstrukcji |

### Wartość zwracana

Inteligentny wskaźnik wskazujący na skonstruowany obiekt [Array](../array/)

## System::MakeArray(Integral, Args\&&...) funkcja


Funkcja fabryczna, która tworzy nowy obiekt [Array](../array/), przekazując określone argumenty do jego konstruktora.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów obiektu [Array](../array/) tworzonego przez funkcję |
| Integral | Typ rozmiaru tablicy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| size | Integral | Rozmiar tworzonej tablicy. |
| args | Args\&&... | Argumenty, które są przekazywane do konstruktora obiektu [Array](../array/) będącego w trakcie konstrukcji |

### Wartość zwracana

Inteligentny wskaźnik wskazujący na skonstruowany obiekt [Array](../array/)

## Zobacz także

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)