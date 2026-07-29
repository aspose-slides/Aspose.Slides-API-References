---
title: CompareExchange()
second_title: Aspose.Slides för C++ API-referens
description: "Jämför och ersätter värde i variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade."
type: docs
weight: 79
url: /sv/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) metod

Jämför- och ersätter värde i variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Variabeltyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | T\& | Referens till variabel som ska ändras. |
| value | T | Värde att lagra. |
| comparand | T | Värde som variabelns värde ska jämföras med innan byte. |

### Returvärde

Variabelns värde vid operationens start oavsett om det ändrades eller inte.

## Interlocked::CompareExchange(T\&, T, T) metod

Jämför- och ersätter värde i variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade. Ej implementerad.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Variabeltyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | T\& | Referens till variabel som ska ändras. |
| value | T | Värde att lagra. |
| comparand | T | Värde som variabelns värde ska jämföras med innan byte. |

### Returvärde

Variabelns värde vid operationens start oavsett om det ändrades eller inte.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) metod

Jämför- och ersätter värde i variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | **int32_t**\& | Referens till variabel som ska ändras. |
| value | **int32_t** | Värde att lagra. |
| comparand | **int32_t** | Värde som variabelns värde ska jämföras med innan byte. |
| succeeded | **bool**\& | Referens till variabel som sätts till true om bytet ägde rum och false annars. |

### Returvärde

Variabelns värde vid operationens start oavsett om det ändrades eller inte.

## Se även

* Klass [Interlocked](../)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)