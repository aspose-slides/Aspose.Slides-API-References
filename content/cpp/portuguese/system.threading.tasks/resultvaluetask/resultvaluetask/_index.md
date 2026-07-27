---
title: ResultValueTask()
second_title: Referência da API do Aspose.Slides para C++
description: Constrói um ResultValueTask vazio e não inicializado.
type: docs
weight: 1
url: /pt/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() construtor


Constrói um [ResultValueTask](../) vazio e não inicializado.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Observações



A tarefa não está concluída e não contém resultado. Tentar obter o resultado lançará uma exceção. 

## ResultValueTask::ResultValueTask(const T\&) construtor


Constrói um [ResultValueTask](../) concluído com o resultado especificado.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| result | const T\& | O valor do resultado a ser encapsulado em uma tarefa concluída. |
## Observações



Isso cria uma tarefa concluída com sucesso que retorna o valor imediatamente. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) construtor


Constrói um [ResultValueTask](../) a partir de um ponteiro compartilhado para um ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | A tarefa a ser encapsulada. Pode ser nula para uma tarefa vazia. |
## Observações



O [ResultValueTask](../) representará o estado e o resultado da tarefa fornecida. 

## Veja Também

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Classe [ResultValueTask](../)
* Espaço de nomes [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)