---
title: Cancel()
second_title: Referência da API Aspose.Slides para C++
description: Comunica uma solicitação de cancelamento.
type: docs
weight: 40
url: /pt/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() método

Comunica uma solicitação de cancelamento.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Observações

Todas as callbacks registradas serão invocadas.

Chamadas subsequentes a [get_IsCancellationRequested()](../get_iscancellationrequested/) retornarão true.

Callbacks são executadas de forma síncrona durante esta chamada.

## Veja Também

* Classe [CancellationTokenSource](../)
* Espaço de nomes [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)