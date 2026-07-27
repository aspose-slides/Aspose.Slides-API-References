---
title: WriteAsync()
second_title: Aspose.Slides for C++ Referência da API
description: Escreve assincronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes escritos e monitora solicitações de cancelamento.
type: docs
weight: 261
url: /pt/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) método

Escreve assincronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes escritos e monitora solicitações de cancelamento.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a serem escritos. |
| offset | **int32_t** | Um índice baseado em 0 do elemento em **buffer** onde a subfaixa a ser escrita começa. |
| count | **int32_t** | O número de elementos na subfaixa a ser escrita. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | O token para monitorar solicitações de cancelamento. |

### Valor de retorno

Uma tarefa que representa a operação de escrita assíncrona.

## Veja Também

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [FileStream](../)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)