---
title: CreateLinkedTokenSource()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma origem de token vinculada que cancela quando qualquer um dos tokens fornecidos é cancelado.
type: docs
weight: 66
url: /pt/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) método

Cria uma origem de token vinculada que cancela quando qualquer um dos tokens fornecidos é cancelado.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Primeiro token de cancelamento a monitorar. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Segundo token de cancelamento a monitorar. |

### Valor de Retorno

Nova origem de token que será cancelada quando qualquer um dos tokens de entrada for cancelado.

## Observações

A origem retornada será cancelada imediatamente se qualquer um dos tokens de entrada já estiver cancelado.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [CancellationTokenSource](../)
* Classe [CancellationToken](../../cancellationtoken/)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)