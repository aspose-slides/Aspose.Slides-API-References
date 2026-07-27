---
title: AsTask()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte este ResultValueTask en un puntero compartido a ResultTask<T>.
type: docs
weight: 79
url: /es/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const método


Convierte este [ResultValueTask](../) en un puntero compartido a ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### Valor de retorno

RTaskPtr<T> Un puntero compartido a ResultTask<T> que representa esta operación.
## Observaciones



Si el [ResultValueTask](../) contiene un resultado directo, crea una tarea completada con ese resultado. Si contiene una tarea, devuelve un puntero compartido a esa tarea. 

## Ver también

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Clase [ResultValueTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)