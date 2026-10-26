---
title: BaseDictionary()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom datastruktur.
type: docs
weight: 14
url: /sv/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() konstruktor

Skapar en tom datastruktur.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) konstruktor

Vidarebefordrande konstruktor för att skicka argument till den underliggande map-konstruktorn.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Args | Typer av argument att vidarebefordra till map. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | int | Argument att vidarebefordra till underliggande map. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) konstruktor

Kopieringskonstruktor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Args | Typer av map-konstruktorsargument. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) för att kopiera data från. |
| args | const Args\&... | Argument att vidarebefordra till underliggande map-konstruktor. |

## BaseDictionary::BaseDictionary(BaseType *) konstruktor

Kopieringskonstruktor.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) för att kopiera data från. |

## Se även

* Typedef [BaseType](../basetype/)
* Klass [BaseDictionary](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)