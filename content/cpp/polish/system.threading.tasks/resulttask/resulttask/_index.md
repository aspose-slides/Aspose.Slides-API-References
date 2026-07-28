---
title: ResultTask()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy ResultTask przy użyciu funkcji, która zwraca wartość.
type: docs
weight: 1
url: /pl/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) konstruktor

Tworzy [ResultTask](../) za pomocą funkcji, która zwraca wartość.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | Funkcja do asynchronicznego wykonania, która zwraca wynik |

## ResultTask::ResultTask() konstruktor

Wewnętrzna implementacja. Nie przeznaczona dla kodu użytkownika.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Uwagi

Wewnętrzny konstruktor tworzący niezinicjowane zadania wynikowe 

## ResultTask::ResultTask(const T\&) konstruktor

Wewnętrzny konstruktor tworzący zadania wynikowe z określonym wynikiem.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Zobacz także

* Klasa [Func](../../../system/func/)
* Klasa [ResultTask](../)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)