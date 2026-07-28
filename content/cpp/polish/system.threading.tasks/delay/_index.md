---
title: Delay()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Tworzy zadanie, które kończy się po upływie określonego czasu.
type: docs
weight: 105
url: /pl/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) funkcja


Tworzy zadanie, które kończy się po upływie określonego czasu.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Liczba milisekund do odczekania przed zakończeniem zwróconego zadania, lub -1 aby czekać w nieskończoność. |

### Wartość zwracana

Zadanie reprezentujące opóźnienie czasowe.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) funkcja


Tworzy zadanie, które kończy się po upływie określonego czasu i może zostać anulowane.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Liczba milisekund do odczekania przed zakończeniem zwróconego zadania, lub -1 aby czekać w nieskończoność. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Token anulowania, który może zostać użyty do anulowania opóźnienia. |

### Wartość zwracana

Zadanie reprezentujące opóźnienie czasowe.

## Zobacz także

* Definicja typu [TaskPtr](../../system/taskptr/)
* Klasa [CancellationToken](../../system.threading/cancellationtoken/)
* Przestrzeń nazw [System::Threading::Tasks](../)
* Biblioteka [Aspose.Slides](../../)