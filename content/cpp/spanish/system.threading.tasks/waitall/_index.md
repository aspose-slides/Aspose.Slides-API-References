---
title: WaitAll()
second_title: Referencia de API de Aspose.Slides para C++
description: Espera a que todos los objetos Task proporcionados completen su ejecución.
type: docs
weight: 170
url: /es/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) función

Espera a que todos los objetos [Task](../task/) proporcionados completen su ejecución.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Una matriz de instancias [Task](../task/) en la que esperar. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Un [CancellationToken](../../system.threading/cancellationtoken/) a observar mientras se espera que las tareas completen. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) función

Espera a que todos los objetos [Task](../task/) proporcionados completen su ejecución.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Una matriz de instancias [Task](../task/) en la que esperar. |

## Véase también

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Clase [CancellationToken](../../system.threading/cancellationtoken/)
* Espacio de nombres [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)