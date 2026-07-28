---
title: SafeInvoke()
second_title: Aspose.Slides dla referencji API C++
description: Implementacja translacji operatora '?.'.
type: docs
weight: 2653
url: /pl/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) funkcja

Implementacja translacji operatora '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T0 | typ wyrażenia. |
| T1 | Typ wyrażenia lambda enkapsulującego wyrażenie 'WhenTrue'. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| expr | T0\&& | wartość wyrażenia. |
| func | T1\&& | wyrażenie 'WhenTrue' powiązane z funktorem. |

### Wartość zwracana

Jeśli wartość expr nie jest nullem, zwraca func wywołane z jej wartością jako pierwszym argumentem, w przeciwnym razie zwraca null.

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)