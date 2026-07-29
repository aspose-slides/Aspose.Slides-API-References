---
title: Nullable()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans som representerar nullvärde.
type: docs
weight: 1
url: /sv/system/nullable/nullable/
---
## Nullable::Nullable() konstruktor


Skapar en instans som representerar nullvärde.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) konstruktor


Skapar en instans som representerar null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) konstruktor


Skapar en instans av [Nullable](../)-klassen som representerar det angivna värdet konverterat (om nödvändigt) till värdet av den underliggande typen T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av det angivna värdet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T1\& | En konstant referens till värdet som ska representeras av det nykonstruerade [Nullable](../)-objektet |

## Nullable::Nullable(const Nullable\<T1\>\&) konstruktor


Skapar en instans som representerar ett värde som representeras av det angivna [Nullable](../)-objektet. Det angivna nullable-objektet kan representera ett värde av en annan typ än den underliggande typen för den konstruerade instansen, varvid det representerade värdet konverteras till en värde av typ T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av det värde som representeras av det angivna [Nullable](../)-objektet |

## Se även

* Klass [Nullable](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)