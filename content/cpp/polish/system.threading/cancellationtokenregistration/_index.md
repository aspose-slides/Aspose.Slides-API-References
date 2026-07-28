---
title: CancellationTokenRegistration
second_title: Odwołanie API Aspose.Slides dla C++
description: Reprezentuje rejestrację wywołania zwrotnego tokenu anulowania.
type: docs
weight: 27
url: /pl/system.threading/cancellationtokenregistration/
---
## Klasa CancellationTokenRegistration

Reprezentuje rejestrację wywołania zwrotnego tokenu anulowania.

```cpp
class CancellationTokenRegistration
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [Dispose](./dispose/)() | Usuwa rejestrację i usuwa wywołanie zwrotne z powiązanego [CancellationTokenSource](../cancellationtokensource/). Po wywołaniu tej metody zarejestrowane wywołanie zwrotne nie będzie już wywoływane, gdy powiązany [CancellationTokenSource](../cancellationtokensource/) zostanie anulowany. |
## Uwagi

Ta klasa umożliwia wyrejestrowanie wywołania zwrotnego z tokenu anulowania. Po usunięciu usuwa wywołanie zwrotne z powiązanego [CancellationTokenSource](../cancellationtokensource/). Ta klasa nie powinna być tworzona bezpośrednio - jest zwracana przez metody rejestracji [CancellationToken](../cancellationtoken/).

## Zobacz także

* Przestrzeń nazw [System::Threading](../)
* Biblioteka [Aspose.Slides](../../)