---
title: GetAwaiter()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene un awaiter para esta tarea de resultado para usar con Await.
type: docs
weight: 53
url: /es/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const método


Obtiene un awaiter para esta tarea de resultado para usar con Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### Valor devuelto

Runtime::CompilerServices::ResultTaskAwaiter<T> Una instancia de awaiter que devuelve el resultado
## Observaciones



Cuando se espera, la corrutina se reanudará con el valor del resultado disponible 

## Ver también

* Clase [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Clase [ResultTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)