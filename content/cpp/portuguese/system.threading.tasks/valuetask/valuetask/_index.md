---
title: ValueTask()
second_title: Referência da API Aspose.Slides for C++
description: Constrói um ValueTask vazio e não inicializado.
type: docs
weight: 1
url: /pt/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() construtor


Constrói um [ValueTask](../) vazio e não inicializado.

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Observações



A tarefa não está concluída e não contém resultado. Tentar obter o resultado lançará uma exceção. 

## ValueTask::ValueTask(const TaskPtr\&) construtor


Constrói um [ValueTask](../) a partir de um ponteiro compartilhado para um [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | A tarefa a envolver. Pode ser nula para uma tarefa vazia. |
## Observações



O [ValueTask](../) representará o estado da tarefa fornecida. 

## Veja Também

* Typedef [TaskPtr](../../../system/taskptr/)
* Classe [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)