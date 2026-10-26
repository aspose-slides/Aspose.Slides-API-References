---
title: Get()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Funkcja służąca do pobrania N-tego elementu podanej krotki. Przeciążenie dla obiektu bazowego.
type: docs
weight: 2406
url: /pl/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) funkcja

Funkcja służąca do pobrania N-tego elementu podanej krotki. Przeciążenie dla obiektu bazowego.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| N | indeks elementu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | obiekt do sprawdzenia. |

### Wartość zwracana

wartość N-tego elementu krotki.

## System::Get(const T\&) funkcja

Funkcja służąca do pobrania N-tego elementu podanej krotki. Przeciążenie dla obiektów z metodą Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| N | indeks elementu. |
| T | typ sprawdzanego obiektu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| object | const T\& | obiekt do sprawdzenia. |

### Wartość zwracana

wartość N-tego elementu krotki.

## System::Get(const SharedPtr\<T\>\&) funkcja

Funkcja służąca do pobrania N-tego elementu podanej krotki. Przeciążenie dla wskaźników współdzielonych.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| N | indeks elementu. |
| T | typ sprawdzanego obiektu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | obiekt do sprawdzenia. |

### Wartość zwracana

wartość N-tego elementu krotki.

## System::Get(T\&, const Index\&) funkcja

Implementacja wyrażeń collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ kolekcji. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| collection | T\& | obiekt kolekcji. |
| index | const [Index](../index/)\& | indeks elementu typu [System.Index](../index/). |

### Wartość zwracana

Element kolekcji na obliczonym przesunięciu.

## System::Get(T\&, const Range\&) funkcja

Zwraca fragment określonej kolekcji określonego zakresem.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| collection | T\& | kolekcja do podzielenia. |
| range | const [Range](../range/)\& | zakres określający granice fragmentu. |

### Wartość zwracana

Widok lub fragment kolekcji od obliczonego początkowego offsetu i długości.

## System::Get(const ValueTuple\<Args...\>\&) funkcja

Pobiera N-ty element krotki wartości.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| N | indeks elementu. |
| Args | elementy krotki. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | krotka, z której pobrać element. |

### Wartość zwracana

wartość N-tego elementu krotki.

## Zobacz także

* Definicja typu [SharedPtr](../sharedptr/)
* Klasa [Object](../object/)
* Klasa [Index](../index/)
* Klasa [Range](../range/)
* Klasa [ValueTuple](../valuetuple/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)