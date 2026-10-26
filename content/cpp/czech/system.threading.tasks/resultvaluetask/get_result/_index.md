---
title: get_Result()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá výsledek dokončeného úkolu.
type: docs
weight: 66
url: /cs/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() method

Získá výsledek dokončeného úkolu.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### Návratová hodnota

T Výsledná hodnota.
## Poznámky

Pokud je úloha podložena ResultTask<T>, tato metoda bude čekat na výsledek a uloží jej do mezipaměti. Následující volání vrátí uloženou hodnotu bez čekání.

## Viz také

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)