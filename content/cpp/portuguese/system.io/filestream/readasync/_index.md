---
title: ReadAsync()
second_title: Referência da API Aspose.Slides para C++
description: Lê de forma assíncrona uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento.
type: docs
weight: 196
url: /pt/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Lê de forma assíncrona uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitoriza solicitações de cancelamento.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes para onde escrever os bytes lidos. |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** onde começar a escrita. |
| count | **int32_t** | O número de bytes a ler. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | O token para monitorar solicitações de cancelamento. |

### Valor de Retorno

Uma tarefa que representa a operação de leitura assíncrona. O valor do parâmetro TResult contém o número total de bytes lidos no buffer. O valor do resultado pode ser menor que o número de bytes solicitado se a quantidade de bytes atualmente disponível for menor que o número solicitado, ou pode ser 0 (zero) se o final do fluxo tiver sido atingido.

## Veja Também

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [FileStream](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)