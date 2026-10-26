---
title: Get()
second_title: Aspose.Slides för C++ API-referens
description: Funktion för att hämta N:te elementet i den givna tupeln. Överlagring för basobjekt.
type: docs
weight: 2406
url: /sv/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) funktion


Funktion för att hämta N:te elementet i den givna tupeln. Överlagring för basobjekt.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| N | element index. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | objekt att inspektera. |

### Returvärde

värdet av N:te tupel-element kastat till objekt.

## System::Get(const T\&) funktion


Funktion för att hämta N:te elementet i den givna tupeln. Överlagring för objekt med Deconstruct-metod.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| N | element index. |
| T | typ av inspekterat objekt. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | const T\& | objekt att inspektera. |

### Returvärde

värdet av N:te tupel-element.

## System::Get(const SharedPtr\<T\>\&) funktion


Funktion för att hämta N:te elementet i den givna tupeln. Överlagring för delade pekare.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| N | element index. |
| T | typ av inspekterat objekt. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | objekt att inspektera. |

### Returvärde

värdet av N:te tupel-element.

## System::Get(T\&, const Index\&) funktion


Implementering för collection[index]-uttryck.

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | samlingstyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| collection | T\& | samlingsobjekt. |
| index | const [Index](../index/)\& | elementindex av typ [System.Index](../index/). |

### Returvärde

Samlingselement vid den beräknade offseten.

## System::Get(T\&, const Range\&) funktion


Returnerar en del av den angivna samlingen som definieras av det angivna intervallet.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| collection | T\& | samlingen att dela. |
| range | const [Range](../range/)\& | intervallet som specificerar delens gränser. |

### Returvärde

En vy eller del av samlingen från den beräknade startoffseten och längden.

## System::Get(const ValueTuple\<Args...\>\&) funktion


Hämtar N:te elementet i värdetupeln.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| N | element index. |
| Args | tupel-element. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | tupel att hämta element från. |

### Returvärde

värdet av N:te tupel-element.

## Se även

* Typdefinition [SharedPtr](../sharedptr/)
* Klass [Object](../object/)
* Klass [Index](../index/)
* Klass [Range](../range/)
* Klass [ValueTuple](../valuetuple/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)