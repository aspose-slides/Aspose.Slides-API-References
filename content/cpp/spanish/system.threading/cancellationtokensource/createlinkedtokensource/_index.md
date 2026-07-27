---
title: CreateLinkedTokenSource()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una fuente de token vinculada que se cancela cuando cualquiera de los tokens proporcionados se cancela.
type: docs
weight: 66
url: /es/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) método

Crea una fuente de token vinculada que se cancela cuando cualquiera de los tokens proporcionados se cancela.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Primer token de cancelación a monitorizar. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Segundo token de cancelación a monitorizar. |

### Valor devuelto

Nueva fuente de token que se cancelará cuando cualquiera de los tokens de entrada se cancele.

## Observaciones

La fuente devuelta se cancelará inmediatamente si alguno de los tokens de entrada ya está cancelado.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [CancellationTokenSource](../)
* Clase [CancellationToken](../../cancellationtoken/)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)