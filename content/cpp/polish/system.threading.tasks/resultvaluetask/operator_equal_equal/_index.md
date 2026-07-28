---
title: operator==()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Operator równości dla ResultValueTask.
type: docs
weight: 131
url: /pl/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const metoda


Operator równości dla [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | Inny [ResultValueTask](../) do porównania z tą instancją. |

### Wartość zwracana

bool True jeśli oba zadania mają tę samą wartość wyniku lub odwołują się do tego samego podstawowego zadania; w przeciwnym razie false.

## Uwagi

Jeśli którakolwiek instancja zawiera bezpośrednią wartość wyniku, porównuje wyniki bezpośrednio. W przeciwnym razie porównuje wskaźniki do podstawowego zadania. 

## Zobacz także

* Klasa [ResultValueTask](../)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)