---
title: Exchange()
second_title: Aspose.Slides för C++ API-referens
description: "Byter värde på variabeln: lagrar det nya värdet och returnerar det värde variabeln hade omedelbart före lagringen."
type: docs
weight: 66
url: /sv/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) metod


Byter värde på variabeln: lagrar det nya värdet och returnerar det värde variabeln hade omedelbart före lagringen.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Variabeltyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | T\& | Variabelreferens att ändra. |
| value | T | Värde att lagra. |

### Returvärde

Variabelns värde precis innan den ändrades.

## Interlocked::Exchange(T\&, T) metod


Byter värde på variabeln: lagrar det nya värdet och returnerar det värde variabeln hade omedelbart före lagringen. Ej implementerad.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Variabeltyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | T\& | Variabelreferens att ändra. |
| value | T | Värde att lagra. |

### Returvärde

Variabelns värde precis innan den ändrades.

## Se även

* Klass [Interlocked](../)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)