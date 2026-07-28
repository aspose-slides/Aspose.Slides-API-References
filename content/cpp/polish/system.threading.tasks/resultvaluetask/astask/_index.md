---
title: AsTask()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konwertuje ten ResultValueTask na wskaźnik współdzielony do ResultTask<T>.
type: docs
weight: 79
url: /pl/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const metoda

Konwertuje ten [ResultValueTask](../) na wskaźnik współdzielony do ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### Wartość zwracana

RTaskPtr<T> Wskaźnik współdzielony do ResultTask<T>, który reprezentuje tę operację.
## Uwagi

Jeśli [ResultValueTask](../) zawiera bezpośredni wynik, tworzy ukończone zadanie z tym wynikiem. Jeśli zawiera zadanie, zwraca wskaźnik współdzielony do tego zadania.

## Zobacz też

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasa [ResultValueTask](../)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)