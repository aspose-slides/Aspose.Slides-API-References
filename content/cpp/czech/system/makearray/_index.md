---
title: MakeArray()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Výrobní funkce, která vytvoří nový objekt Array, naplní jej prvky ze zadaného seznamu inicializace a vrátí chytrý ukazatel ukazující na objekt Array.
type: docs
weight: 2029
url: /cs/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) funkce

Výrobní funkce, která vytvoří nový objekt [Array](../array/), naplní jej prvky ze zadaného seznamu inicializace a vrátí chytrý ukazatel ukazující na objekt [Array](../array/).

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků objektu [Array](../array/), který funkce konstruuje |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| init | std::initializer_list\<T\> | Seznam inicializace obsahující prvky, kterými bude pole naplněno |

### Návratová hodnota

Chytrý ukazatel ukazující na vytvořený objekt [Array](../array/)

## System::MakeArray(Args\&&...) funkce

Výrobní funkce, která vytvoří nový objekt [Array](../array/) a předá určené argumenty jeho konstruktoru.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků objektu [Array](../array/), který funkce konstruuje |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| args | Args\&&... | Argumenty, které jsou předány konstruktoru objektu [Array](../array/) při jeho vytváření |

### Návratová hodnota

Chytrý ukazatel ukazující na vytvořený objekt [Array](../array/)

## System::MakeArray(Integral, Args\&&...) funkce

Výrobní funkce, která vytvoří nový objekt [Array](../array/) a předá určené argumenty jeho konstruktoru.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků objektu [Array](../array/), který funkce konstruuje |
| Integral | Typ velikosti pole. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| size | Integral | Velikost vytvářeného pole. |
| args | Args\&&... | Argumenty, které jsou předány konstruktoru objektu [Array](../array/) při jeho vytváření |

### Návratová hodnota

Chytrý ukazatel ukazující na vytvořený objekt [Array](../array/)

## Viz také

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)