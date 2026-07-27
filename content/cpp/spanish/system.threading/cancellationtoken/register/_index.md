---
title: Register()
second_title: Referencia de la API de Aspose.Slides para C++
description: Registra un callback que se invocará cuando se solicite la cancelación.
type: docs
weight: 40
url: /es/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const método

Registra un callback que se invocará cuando se solicite la cancelación.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | La Action<> para ejecutar cuando se solicite la cancelación. |

### Valor de retorno

Un objeto [CancellationTokenRegistration](../../cancellationtokenregistration/) que puede usarse para anular el registro del callback.

## Comentarios

Si la cancelación ya ha sido solicitada, el callback se invocará inmediatamente. 

El callback debe ser de corta duración y no bloqueante, ya que se ejecutará en el hilo que llama a Cancel() en el [CancellationTokenSource](../../cancellationtokensource/). 

## Ver también

* Typedef [Action](../../../system/action/)
* Clase [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Clase [CancellationToken](../)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)