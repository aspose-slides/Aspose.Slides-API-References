---
title: FromCanceled()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una tarea que ha finalizado debido a la cancelación con el token especificado.
type: docs
weight: 118
url: /es/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) función

Crea una tarea que ha finalizado debido a la cancelación con el token especificado.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | El token de cancelación que causó que la tarea fuera cancelada. |

### Valor devuelto

Una tarea cancelada.

## Véase también

* Typedef [TaskPtr](../../system/taskptr/)
* Clase [CancellationToken](../../system.threading/cancellationtoken/)
* Espacio de nombres [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)