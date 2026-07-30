---
title: ResultTask()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Vytvoří objekt ResultTask s funkcí, která vrací hodnotu.
type: docs
weight: 1
url: /cs/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) konstruktor


Constructs a [ResultTask](../) with a function that returns a value.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | Funkce, která se má asynchronně spustit a vrátí výsledek |

## ResultTask::ResultTask() konstruktor


Interní implementace. Není určena pro uživatelský kód.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Poznámky


Interní konstruktor pro vytváření neinitializovaných úkolů výsledků 
## ResultTask::ResultTask(const T\&) konstruktor


Interní konstruktor pro vytváření úkolů výsledků se specifikovaným výsledkem.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Viz také

* Třída [Func](../../../system/func/)
* Třída [ResultTask](../)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)