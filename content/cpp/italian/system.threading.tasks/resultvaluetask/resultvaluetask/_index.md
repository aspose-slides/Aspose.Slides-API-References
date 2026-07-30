---
title: ResultValueTask()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un ResultValueTask vuoto e non inizializzato.
type: docs
weight: 1
url: /it/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() costruttore


Crea un [ResultValueTask](../) vuoto e non inizializzato.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Osservazioni



L'attività non è completata e non contiene alcun risultato. Tentare di ottenere il risultato genererà un'eccezione. 

## ResultValueTask::ResultValueTask(const T\&) costruttore


Crea un [ResultValueTask](../) completato con il risultato specificato.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| result | const T\& | Il valore del risultato da avvolgere in un'attività completata. |
## Osservazioni



Questo crea un'attività completata con successo che restituisce immediatamente il valore. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) costruttore


Crea un [ResultValueTask](../) da un puntatore condiviso a un ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | L'attività da avvolgere. Può essere null per un'attività vuota. |
## Osservazioni



Il [ResultValueTask](../) rappresenterà lo stato e il risultato dell'attività fornita. 

## Vedi anche

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Classe [ResultValueTask](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)