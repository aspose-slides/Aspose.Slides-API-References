---
title: FlushAsync()
second_title: Referência da API Aspose.Slides para C++
description: Limpa assincronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados em buffer sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento.
type: docs
weight: 157
url: /pt/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) método

Limpa assincronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados em buffer sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | O token a ser monitorado para solicitações de cancelamento. |

### Valor de Retorno

Uma tarefa que representa a operação de flush assíncrona.

## Veja Também

* Typedef [TaskPtr](../../../system/taskptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [FileStream](../)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)