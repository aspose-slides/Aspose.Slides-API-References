---
title: FromResult()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una tarea que ha finalizado con éxito con el resultado especificado.
type: docs
weight: 144
url: /es/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult(TResult) función


Crea una tarea que ha finalizado con éxito con el resultado especificado.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo del resultado de la tarea. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| result | TResult | El valor del resultado con el que completar la tarea. |

### Valor devuelto

Una tarea completada con éxito.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Espacio de nombres [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)