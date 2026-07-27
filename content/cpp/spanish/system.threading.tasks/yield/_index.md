---
title: Yield()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una tarea awaitable que de forma asincrónica cede el control al contexto actual cuando se espera.
type: docs
weight: 222
url: /es/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() función


Crea una tarea awaitable que, de forma asincrónica, cede la ejecución al contexto actual cuando se espera.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### Valor de retorno

Un YieldAwaitable que puede esperarse para ceder el control.
## Observaciones



Este método es útil para forzar que un método asincrónico ceda el control, permitiendo que se procesen otras tareas pendientes antes de continuar. 
## Ver también

* Clase [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Espacio de nombres [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)