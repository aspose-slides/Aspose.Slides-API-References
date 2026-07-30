---
title: operator==()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Operátor rovnosti pro ResultValueTask.
type: docs
weight: 131
url: /cs/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const metoda


Operátor rovnosti pro [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | Druhý [ResultValueTask](../) pro porovnání s touto instancí. |

### Návratová hodnota

bool True, pokud mají oba úkoly stejnou výslednou hodnotu nebo odkazují na stejný podkladový úkol; jinak false.
## Poznámky



Pokud některá instance obsahuje přímou výslednou hodnotu, porovnává výsledky přímo. Jinak porovnává ukazatele na podkladový úkol. 
## Viz také

* Třída [ResultValueTask](../)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)