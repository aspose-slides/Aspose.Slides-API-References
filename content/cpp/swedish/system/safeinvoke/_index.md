---
title: SafeInvoke()
second_title: Aspose.Slides för C++ API-referens
description: Implementation av översättning av operatorn '?.'.
type: docs
weight: 2653
url: /sv/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) funktion

Implementering av översättning av operatorn '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T0 | uttryckstyp. |
| T1 | Typ av lambda som kapslar in 'WhenTrue'-uttrycket. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expr | T0\&& | uttrycksvärde. |
| func | T1\&& | 'WhenTrue'-uttryck bundet till funktor. |

### Returvärde

Om expr-värdet inte är null, returneras func anropad med dess värde som första argument, annars returneras null.

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)