---
title: ResultValueTask()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy pusty, niezainicjowany ResultValueTask.
type: docs
weight: 1
url: /pl/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() konstruktor


Tworzy pustą, niezainicjowaną [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Uwagi



Zadanie nie jest zakończone i nie zawiera wyniku. Próba pobrania wyniku spowoduje wyrzucenie wyjątku. 

## ResultValueTask::ResultValueTask(const T\&) konstruktor


Tworzy zakończoną [ResultValueTask](../) z określonym wynikiem.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| result | const T\& | Wartość wyniku do opakowania w zakończonym zadaniu. |
## Uwagi



Tworzy pomyślnie zakończone zadanie, które natychmiast zwraca wartość. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) konstruktor


Tworzy [ResultValueTask](../) z udostępnionego wskaźnika do ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | Zadanie do opakowania. Może być null dla pustego zadania. |
## Uwagi



[ResultValueTask](../) będzie reprezentował stan i wynik dostarczonego zadania. 

## Zobacz także

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasa [ResultValueTask](../)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)