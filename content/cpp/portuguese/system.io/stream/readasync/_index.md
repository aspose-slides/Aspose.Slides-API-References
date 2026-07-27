---
title: ReadAsync()
second_title: Referência da API Aspose.Slides para C++
description: Lê de forma assíncrona uma sequência de bytes do fluxo atual, avança a posição no fluxo pelo número de bytes lidos e monitora solicitações de cancelamento.
type: docs
weight: 40
url: /pt/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) método


Lê de forma assíncrona uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes para onde escrever os bytes lidos. |
| offset | **int32_t** | Uma posição baseada em 0 em **buffer** para iniciar a gravação. |
| count | **int32_t** | O número de bytes a ler. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | O token a ser monitorado para solicitações de cancelamento. |

### Valor de Retorno

Uma tarefa que representa a operação de leitura assíncrona. O valor do parâmetro TResult contém o número total de bytes lidos para o buffer. O valor de resultado pode ser menor que o número de bytes solicitados se o número de bytes atualmente disponíveis for menor que o solicitado, ou pode ser 0 (zero) se o final do fluxo tiver sido alcançado.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Lê de forma assíncrona uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes para onde escrever os bytes lidos. |
| offset | **int32_t** | Uma posição baseada em 0 em **buffer** para iniciar a gravação. |
| count | **int32_t** | O número de bytes a ler. |

### Valor de Retorno

Uma tarefa que representa a operação de leitura assíncrona. O valor do parâmetro TResult contém o número total de bytes lidos para o buffer. O valor de resultado pode ser menor que o número de bytes solicitados se o número de bytes atualmente disponíveis for menor que o solicitado, ou pode ser 0 (zero) se o final do fluxo tiver sido alcançado.

## Ver Também

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Stream](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)