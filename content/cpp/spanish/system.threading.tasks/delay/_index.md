---
title: Delay()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una tarea que se completa después de un retraso de tiempo.
type: docs
weight: 105
url: /es/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) función


Crea una tarea que se completa después de un retraso de tiempo, o -1 para esperar indefinidamente.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | El número de milisegundos a esperar antes de completar la tarea devuelta, o -1 para esperar indefinidamente. |

### Valor de retorno

Una tarea que representa el retraso de tiempo.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) función


Crea una tarea que se completa después de un retraso de tiempo y puede cancelarse.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | El número de milisegundos a esperar antes de completar la tarea devuelta, o -1 para esperar indefinidamente. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | El token de cancelación que puede usarse para cancelar el retraso. |

### Valor de retorno

Una tarea que representa el retraso de tiempo.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)