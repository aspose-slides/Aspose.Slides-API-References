---
title: BaseDictionary()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Tworzy pustą strukturę danych.
type: docs
weight: 14
url: /pl/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() konstruktor

Utworzy pustą strukturę danych.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) konstruktor

Konstruktor przekazujący argumenty do konstruktora podkładowej mapy.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Args | Typy argumentów przekazywanych do mapy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | int | Argumenty przekazywane do podkładowej mapy. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) konstruktor

Konstruktor kopiujący.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Args | Typy argumentów konstruktora mapy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) do skopiowania danych z. |
| args | const Args\&... | Argumenty przekazywane do podkładowego konstruktora mapy. |

## BaseDictionary::BaseDictionary(BaseType *) konstruktor

Konstruktor kopiujący.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) do skopiowania danych z. |

## Zobacz też

* Typedef [BaseType](../basetype/)
* Klasa [BaseDictionary](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)