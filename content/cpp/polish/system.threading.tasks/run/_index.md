---
title: Run()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Umieszcza określone zadanie w kolejce do wykonania w puli wątków i zwraca uchwyt Task dla tego zadania.
type: docs
weight: 157
url: /pl/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) funkcja


Umieszcza określone zadanie w kolejce do wykonania w puli wątków i zwraca uchwyt [Task](../task/) do tego zadania.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Zadanie do wykonania asynchronicznie. |

### Wartość zwracana

[Task](../task/) reprezentujący zadanie umieszczone w kolejce do wykonania w puli wątków.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) funkcja


Umieszcza określone zadanie w kolejce do wykonania w puli wątków i zwraca uchwyt [Task](../task/) do tego zadania.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Zadanie do wykonania asynchronicznie. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Token anulowania, który może zostać użyty do anulowania zadania, jeśli nie zostało jeszcze rozpoczęte. |

### Wartość zwracana

[Task](../task/) reprezentujący zadanie umieszczone w kolejce do wykonania w puli wątków.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) funkcja


Umieszcza określone zadanie w kolejce do wykonania w puli wątków i zwraca proxy dla [Task](../task/) zwróconego przez funkcję.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Zadanie do wykonania asynchronicznie, które zwraca [Task](../task/). |

### Wartość zwracana

[Task](../task/) reprezentujący proxy dla [Task](../task/) zwróconego przez funkcję.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) funkcja


Umieszcza określone zadanie w kolejce do wykonania w puli wątków i zwraca uchwyt Task<TResult> do tego zadania.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TResult | Typ wyniku zwracanego przez zadanie. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Zadanie do wykonania asynchronicznie. |

### Wartość zwracana

Task<TResult> reprezentujący zadanie umieszczone w kolejce do wykonania w puli wątków.

## Zobacz także

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Klasa [CancellationToken](../../system.threading/cancellationtoken/)
* Klasa [Func](../../system/func/)
* Przestrzeń nazw [System::Threading::Tasks](../)
* Biblioteka [Aspose.Slides](../../)