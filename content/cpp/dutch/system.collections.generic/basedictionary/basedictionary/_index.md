---
title: BaseDictionary()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een lege datastructuur aan.
type: docs
weight: 14
url: /nl/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() constructor

Maakt een lege datastructuur aan.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) constructor

Doorstuurende constructor om argumenten door te geven aan de onderliggende mapconstructor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Args | Types of arguments to forward to map. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | int | Argumenten om door te geven aan de onderliggende map. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) constructor

Kopieerconstructor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Args | Types of map constructor arguments. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) om gegevens van te kopiëren. |
| args | const Args\&... | Argumenten om door te geven aan de onderliggende mapconstructor. |

## BaseDictionary::BaseDictionary(BaseType *) constructor

Kopieerconstructor.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) om gegevens van te kopiëren. |

## Zie ook

* Typedef [BaseType](../basetype/)
* Klasse [BaseDictionary](../)
* Namespace [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)