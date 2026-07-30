---
title: Get()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Funkce pro získání N-tého prvku z dané n-tice. Přetížení pro základní objekt.
type: docs
weight: 2406
url: /cs/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) funkce

Funkce pro získání N-tého prvku zadané n-tice. Přetížení pro základní objekt.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| N | index prvku. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | objekt k prozkoumání. |

### Návratová hodnota

hodnota N-tého prvku n-tice přetypovaná na objekt.

## System::Get(const T\&) funkce

Funkce pro získání N-tého prvku zadané n-tice. Přetížení pro objekty s metodou Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| N | index prvku. |
| T | typ prozkoumaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| object | const T\& | objekt k prozkoumání. |

### Návratová hodnota

hodnota N-tého prvku n-tice.

## System::Get(const SharedPtr\<T\>\&) funkce

Funkce pro získání N-tého prvku zadané n-tice. Přetížení pro sdílené ukazatele.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| N | index prvku. |
| T | typ prozkoumaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | objekt k prozkoumání. |

### Návratová hodnota

hodnota N-tého prvku n-tice.

## System::Get(T\&, const Index\&) funkce

Implementace pro výrazy collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ kolekce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| collection | T\& | Objekt kolekce. |
| index | const [Index](../index/)\& | Index prvku typu [System.Index](../index/). |

### Návratová hodnota

Prvek kolekce na vypočteném posunu.

## System::Get(T\&, const Range\&) funkce

Vrací výřez zadané kolekce definovaný zadaným rozsahem.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| collection | T\& | Kolekce, která se má rozřezat. |
| range | const [Range](../range/)\& | Rozsah určující hranice výřezu. |

### Návratová hodnota

Pohled nebo výřez kolekce od vypočteného počátečního posunu a délky.

## System::Get(const ValueTuple\<Args...\>\&) funkce

Získá N-tý prvek hodnotové n-tice.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| N | index prvku. |
| Args | prvky n-tice. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | n-tice, ze které se má získat prvek. |

### Návratová hodnota

hodnota N-tého prvku n-tice.

## Viz také

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Index](../index/)
* Class [Range](../range/)
* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)