---
title: BaseDictionary()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří prázdnou datovou strukturu.
type: docs
weight: 14
url: /cs/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() konstruktor

Vytvoří prázdnou datovou strukturu.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) konstruktor

Přeposílací konstruktor, který předá argumenty do konstruktoru podkladové mapy.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Args | Typy argumentů, které se předají mapě. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| args | int | Argumenty, které se předají podkladové mapě. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) konstruktor

Kopírovací konstruktor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Args | Typy argumentů konstruktoru mapy. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) ke kopírování dat z. |
| args | const Args\&... | Argumenty, které se předají konstruktoru podkladové mapy. |

## BaseDictionary::BaseDictionary(BaseType *) konstruktor

Kopírovací konstruktor.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) ke kopírování dat z. |

## Viz také

* Typedef [BaseType](../basetype/)
* Třída [BaseDictionary](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)