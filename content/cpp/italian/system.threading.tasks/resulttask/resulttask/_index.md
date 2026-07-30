---
title: ResultTask()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisce un ResultTask con una funzione che restituisce un valore.
type: docs
weight: 1
url: /it/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) costruttore


Costruisce un [ResultTask](../) con una funzione che restituisce un valore.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | La funzione da eseguire in modo asincrono che restituisce un risultato |

## ResultTask::ResultTask() costruttore


Implementazione interna. Non per codice utente.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Osservazioni


Costruttore interno per la creazione di task di risultato non inizializzati 
## ResultTask::ResultTask(const T\&) costruttore


Costruttore interno per creare task di risultato con risultato specificato.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Vedi anche

* Classe [Func](../../../system/func/)
* Classe [ResultTask](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)