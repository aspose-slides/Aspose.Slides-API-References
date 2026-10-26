---
title: FlushAsync()
second_title: Referência da API Aspose.Slides para C++
description: Limpa assincronamente todos os buffers deste fluxo, faz com que quaisquer dados em buffer sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento.
type: docs
weight: 118
url: /pt/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) método

Limpa assincronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados em buffer sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | O token a ser monitorado para solicitações de cancelamento. |

### Valor de Retorno

Uma tarefa que representa a operação de flush assíncrona.

## Stream::FlushAsync() método

Limpa assincronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados em buffer sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### Valor de Retorno

Uma tarefa que representa a operação de flush assíncrona.

## Veja Também

* Typedef [TaskPtr](../../../system/taskptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Stream](../)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)