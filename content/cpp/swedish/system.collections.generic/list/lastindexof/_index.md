---
title: LastIndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter det specificerade objektet och returnerar det nollbaserade indexet för den sista förekomsten i hela listan.
type: docs
weight: 469
url: /sv/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const metod

Söker efter det specificerade objektet och returnerar det nollbaserade indexet för den sista förekomsten i hela listan.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const T\& | Objektet att hitta i listan |

### Returvärde

Det nollbaserade indexet för den sista förekomsten av item inom hela [List](../), om det finns; annars -1.

## List::LastIndexOf(const T\&, int32_t) const metod

Söker efter det specificerade objektet och returnerar det nollbaserade indexet för den sista förekomsten inom intervallet av element i [List](../) som sträcker sig från det första elementet till det angivna indexet.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const T\& | Objektet att hitta i listan |
| index | **int32_t** | Det nollbaserade startindexet för den bakåtsökning. |

### Returvärde

Det nollbaserade indexet för den sista förekomsten av item inom intervallet av element i [List](../) som sträcker sig från det första elementet till index, om det finns; annars -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const metod

Söker efter det specificerade objektet och returnerar det nollbaserade indexet för den sista förekomsten inom intervallet av element i [List](../) som innehåller det angivna antalet element och avslutas vid det angivna indexet.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const T\& | Objektet att hitta i [List](../) |
| index | **int32_t** | Det nollbaserade startindexet för den bakåtsökning. |
| count | **int32_t** | Antalet element i avsnittet som skall sökas. |

### Returvärde

Det nollbaserade indexet för den sista förekomsten av item inom intervallet av element i [List](../) som innehåller count antal element och avslutas vid index, om det finns; annars -1.

## Se även

* Klass [List](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)