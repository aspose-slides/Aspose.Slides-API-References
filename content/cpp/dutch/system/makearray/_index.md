---
title: MakeArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Een fabrieksfunctie die een nieuw Array-object maakt, het vult met de elementen uit de opgegeven initialisatielijst en een smart pointer retourneert die naar het Array-object wijst.
type: docs
weight: 2029
url: /nl/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) functie


Een fabrieksfunctie die een nieuw [Array](../array/)-object maakt, het vult met de elementen uit de opgegeven initialisatielijst en een smart pointer retourneert die naar het [Array](../array/)-object wijst.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen van het [Array](../array/)-object dat de functie maakt |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| init | std::initializer_list\<T\> | De initialisatielijst die de elementen bevat waarmee de array wordt gevuld |

### Retourwaarde

Een smart pointer die naar het geconstrueerde [Array](../array/)-object wijst

## System::MakeArray(Args\&&...) functie


Een fabrieksfunctie die een nieuw [Array](../array/)-object maakt en de opgegeven argumenten doorgeeft aan diens constructor.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen van het [Array](../array/)-object dat de functie maakt |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | Args\&&... | De argumenten die aan de constructor van het [Array](../array/)-object worden doorgegeven dat wordt geconstrueerd |

### Retourwaarde

Een smart pointer die naar het geconstrueerde [Array](../array/)-object wijst

## System::MakeArray(Integral, Args\&&...) functie


Een fabrieksfunctie die een nieuw [Array](../array/)-object maakt en de opgegeven argumenten doorgeeft aan diens constructor.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen van het [Array](../array/)-object dat de functie maakt |
| Integral | Type van de arraygrootte. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | Integral | Grootte van de te maken array. |
| args | Args\&&... | De argumenten die aan de constructor van het [Array](../array/)-object worden doorgegeven dat wordt geconstrueerd |

### Retourwaarde

Een smart pointer die naar het geconstrueerde [Array](../array/)-object wijst

## Zie ook

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)