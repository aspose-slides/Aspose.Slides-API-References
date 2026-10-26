---
title: ResultValueTask()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří prázdný, neinicializovaný ResultValueTask.
type: docs
weight: 1
url: /cs/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() konstruktor

Vytvoří prázdný, neinicializovaný [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Poznámky



Úkol není dokončen a neobsahuje žádný výsledek. Pokus o získání výsledku vyvolá výjimku. 

## ResultValueTask::ResultValueTask(const T\&) konstruktor


Vytvoří dokončený [ResultValueTask](../) se zadaným výsledkem.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| result | const T\& | Hodnota výsledku, která bude zabalená do dokončeného úkolu. |
## Poznámky



Tímto se vytvoří úspěšně dokončený úkol, který okamžitě vrátí hodnotu. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) konstruktor


Vytvoří [ResultValueTask](../) ze sdíleného ukazatele na ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | Úkol, který bude zabalen. Může být null pro prázdný úkol. |
## Poznámky



[ResultValueTask](../) bude představovat stav a výsledek poskytnutého úkolu. 

## Viz také

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Třída [ResultValueTask](../)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)