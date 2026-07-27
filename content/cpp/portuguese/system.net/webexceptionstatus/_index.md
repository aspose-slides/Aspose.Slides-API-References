---
title: WebExceptionStatus
second_title: Referência da API Aspose.Slides para C++
description: Enumera os códigos de status da classe WebException.
type: docs
weight: 651
url: /pt/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Enumera os códigos de status da classe WebException.

```cpp
enum class WebExceptionStatus
```

### Values

| Nome | Valor | Descrição |
| --- | --- | --- |
| Success | 0 | Nenhum erro ocorreu. |
| NameResolutionFailure | 1 | O serviço de resolução de nomes não pôde resolver o nome do host. |
| ConnectFailure | 2 | O ponto de serviço remoto não pôde ser contatado no nível de transporte. |
| ReceiveFailure | 3 | Uma resposta completa não foi recebida do servidor remoto. |
| SendFailure | 4 | Uma solicitação completa não pôde ser enviada ao servidor remoto. |
| PipelineFailure | 5 | A solicitação era uma solicitação em pipeline e a conexão foi fechada antes que a resposta fosse recebida. |
| RequestCanceled | 6 | A solicitação foi cancelada ou ocorreu um erro não classificável. |
| ProtocolError | 7 | A resposta recebida do servidor estava completa, mas indicava um erro em nível de protocolo. |
| ConnectionClosed | 8 | A conexão foi fechada prematuramente. |
| TrustFailure | 9 | Um certificado do servidor não pôde ser validado. |
| SecureChannelFailure | 10 | Ocorreu um erro ao estabelecer uma conexão usando SSL. |
| ServerProtocolViolation | 11 | A resposta do servidor não era uma resposta HTTP válida. |
| KeepAliveFailure | 12 | A conexão para uma solicitação que especifica o cabeçalho 'Keep-Alive' foi fechada inesperadamente. |
| Pending | 13 | Uma solicitação assíncrona interna está pendente. |
| Timeout | 14 | Nenhuma resposta foi recebida durante o período de timeout de uma solicitação. |
| ProxyNameResolutionFailure | 15 | O serviço de resolução de nomes não pôde resolver o nome do host do proxy. |
| UnknownError | 16 | Uma exceção de tipo desconhecido ocorreu. |
| MessageLengthLimitExceeded | 17 | Uma mensagem que excedeu o limite especificado foi recebida. |
| CacheEntryNotFound | 18 | A entrada de cache especificada não foi encontrada. |
| RequestProhibitedByCachePolicy | 19 | A solicitação não foi permitida pela política de cache. |
| RequestProhibitedByProxy | 20 | Esta solicitação não foi permitida pelo proxy. |

## Veja Também

* Namespace [System::Net](../)
* Biblioteca [Aspose.Slides](../../)