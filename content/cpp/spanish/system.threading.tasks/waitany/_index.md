---
title: WaitAny()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera a que cualquiera de los objetos Task proporcionados complete la ejecución.
type: docs
weight: 183
url: /es/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) función

Espera a que cualquiera de los objetos [Task](../task/) proporcionados complete la ejecución.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Una matriz de instancias de [Task](../task/) en la que se espera. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Un [CancellationToken](../../system.threading/cancellationtoken/) para observar mientras se espera que las tareas se completen. |

### Valor de retorno

El índice de la tarea completada en el array de tasks.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) función

Espera a que cualquiera de los objetos [Task](../task/) proporcionados complete la ejecución.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Una matriz de instancias de [Task](../task/) en la que se espera. |

### Valor de retorno

El índice de la tarea completada en el array de tasks.

## Ver también

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)