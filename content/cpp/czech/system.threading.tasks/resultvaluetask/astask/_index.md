---
title: AsTask()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převede tento ResultValueTask na sdílený ukazatel na ResultTask<T>.
type: docs
weight: 79
url: /cs/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const metoda

Převede tento [ResultValueTask](../) na sdílený ukazatel na ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### Návratová hodnota

RTaskPtr<T> Sdílený ukazatel na ResultTask<T>, který představuje tuto operaci.
## Poznámky

Pokud [ResultValueTask](../) obsahuje přímý výsledek, vytvoří dokončený úkol s tímto výsledkem. Pokud obsahuje úkol, vrátí sdílený ukazatel na tento úkol. 

## Viz také

* Definice typu [RTaskPtr](../../../system/rtaskptr/)
* Třída [ResultValueTask](../)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)