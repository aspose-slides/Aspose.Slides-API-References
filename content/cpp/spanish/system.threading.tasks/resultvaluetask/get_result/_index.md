---
title: get_Result()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el resultado de la tarea completada.
type: docs
weight: 66
url: /es/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() method

Obtiene el resultado de la tarea completada.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### Valor de retorno

T El valor del resultado.
## Comentarios

Si la tarea está respaldada por un ResultTask<T>, este método esperará el resultado y lo almacenará en caché. Las llamadas posteriores devolverán el valor almacenado en caché sin esperar.

## Véase también

* Clase [ResultValueTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)