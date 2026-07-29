---
title: MakeArray()
second_title: Aspose.Slides för C++ API-referens
description: En fabrikfunktion som skapar ett nytt Array-objekt, fyller det med element från den angivna initieringslistan och returnerar en smart pekare som pekar på Array-objektet.
type: docs
weight: 2029
url: /sv/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) funktion


En fabrikfunktion som skapar ett nytt [Array](../array/)-objekt, fyller det med element från den angivna initieringslistan och returnerar en smart pekare som pekar på [Array](../array/)-objektet.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i [Array](../array/)-objektet som funktionen konstruerar |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| init | std::initializer_list\<T\> | Initieringslistan som innehåller elementen för att fylla arrayen med |

### Returvärde

En smart pekare som pekar på det konstruerade [Array](../array/)-objektet

## System::MakeArray(Args\&&...) funktion


En fabrikfunktion som skapar ett nytt [Array](../array/)-objekt och skickar de angivna argumenten till dess konstruktor.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i [Array](../array/)-objektet som funktionen konstruerar |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | Args\&&... | Argumenten som skickas till konstruktorn för [Array](../array/)-objektet som konstrueras |

### Returvärde

En smart pekare som pekar på det konstruerade [Array](../array/)-objektet

## System::MakeArray(Integral, Args\&&...) funktion


En fabrikfunktion som skapar ett nytt [Array](../array/)-objekt och skickar de angivna argumenten till dess konstruktor.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i [Array](../array/)-objektet som funktionen konstruerar |
| Integral | Typ av arraystorlek. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | Integral | Storleken på arrayen som skapas. |
| args | Args\&&... | Argumenten som skickas till konstruktorn för [Array](../array/)-objektet som konstrueras |

### Returvärde

En smart pekare som pekar på det konstruerade [Array](../array/)-objektet

## Se även

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)