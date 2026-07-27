---
title: WriteAsync()
second_title: Referência da API Aspose.Slides para C++
description: Grava assincronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes gravados e monitora solicitações de cancelamento.
type: docs
weight: 66
url: /pt/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) método

Grava assincronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes gravados e monitora solicitações de cancelamento.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a serem gravados. |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde a subfaixa a ser gravada começa. |
| count | **int32_t** | O número de elementos na subfaixa a ser gravada. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | O token a ser monitorado para solicitações de cancelamento. |

### Valor de Retorno

Uma tarefa que representa a operação de gravação assíncrona.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Grava assincronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes gravados e monitora solicitações de cancelamento.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a serem gravados. |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde a subfaixa a ser gravada começa. |
| count | **int32_t** | O número de elementos na subfaixa a ser gravada. |

### Valor de Retorno

Uma tarefa que representa a operação de gravação assíncrona.

## Veja Também

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Stream](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)