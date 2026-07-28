---
title: get_Result()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca wynik zakończonego zadania.
type: docs
weight: 66
url: /pl/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() metoda

Zwraca wynik zakończonego zadania.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### Wartość zwracana

T Wartość wyniku.
## Uwagi

Jeśli zadanie jest obsługiwane przez ResultTask<T>, ta metoda poczeka na wynik i zapisze go w pamięci podręcznej. Kolejne wywołania zwrócą zapisaną wartość bez oczekiwania. 

## Zobacz także

* Klasa [ResultValueTask](../)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)