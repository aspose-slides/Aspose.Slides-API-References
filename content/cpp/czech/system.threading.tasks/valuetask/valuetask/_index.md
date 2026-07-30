---
title: ValueTask()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří prázdný, neinicializovaný ValueTask.
type: docs
weight: 1
url: /cs/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() konstruktor


Vytvoří prázdný, neinicializovaný [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Poznámky



Úloha není dokončena a neobsahuje žádný výsledek. Pokus o získání výsledku vyvolá výjimku. 

## ValueTask::ValueTask(const TaskPtr\&) konstruktor


Vytvoří [ValueTask](../) ze sdíleného ukazatele na [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | Úloha k zabalení. Může být null pro prázdnou úlohu. |
## Poznámky



[ValueTask](../) bude představovat stav poskytnuté úlohy. 

## Viz také

* Typedef [TaskPtr](../../../system/taskptr/)
* Třída [ValueTask](../)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)