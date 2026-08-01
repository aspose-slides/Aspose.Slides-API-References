---
title: Get()
second_title: Aspose.Slides voor C++ API-referentie
description: Functie om het N-de element van de opgegeven tuple te verkrijgen. Overload voor basisobject.
type: docs
weight: 2406
url: /nl/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) functie

Functie om het N-de element van de gegeven tuple te verkrijgen. Overload voor basisobject.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| N | elementindex. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | object om te inspecteren. |

### Retourwaarde

waarde van het N-de tuple-element omgezet naar object.

## System::Get(const T\&) functie

Functie om het N-de element van de gegeven tuple te verkrijgen. Overload voor objecten met Deconstruct-methode.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| N | elementindex. |
| T | type van het geinspecteerde object. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| object | const T\& | object om te inspecteren. |

### Retourwaarde

waarde van het N-de tuple-element.

## System::Get(const SharedPtr\<T\>\&) functie

Functie om het N-de element van de gegeven tuple te verkrijgen. Overload voor gedeelde pointers.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| N | elementindex. |
| T | type van het geinspecteerde object. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | object om te inspecteren. |

### Retourwaarde

waarde van het N-de tuple-element.

## System::Get(T\&, const Index\&) functie

Implementatie voor collection[index]-expressies.

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Collectietype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| collection | T\& | Collectie-object. |
| index | const [Index](../index/)\& | Element-index van type [System.Index](../index/). |

### Retourwaarde

Collectie-element op de berekende offset.

## System::Get(T\&, const Range\&) functie

Retourneert een slice van de opgegeven collectie gedefinieerd door het opgegeven bereik.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| collection | T\& | De collectie om te slicen. |
| range | const [Range](../range/)\& | Het bereik dat de slice-grenzen specificeert. |

### Retourwaarde

Een weergave of slice van de collectie vanaf de berekende start-offset en lengte.

## System::Get(const ValueTuple\<Args...\>\&) functie

Haalt het N-de element van de waardetuples op.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| N | elementindex. |
| Args | tuple-elementen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | tuple om element uit te halen. |

### Retourwaarde

waarde van het N-de tuple-element.

## Zie ook

* Typedef [SharedPtr](../sharedptr/)
* Klasse [Object](../object/)
* Klasse [Index](../index/)
* Klasse [Range](../range/)
* Klasse [ValueTuple](../valuetuple/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)