---
title: SocketError
second_title: Referência da API Aspose.Slides para C++
description: Enumera os tipos de erro de socket.
type: docs
weight: 209
url: /pt/system.net.sockets/socketerror/
---
## SocketError enum

Enumera os tipos de erro de socket.

```cpp
enum class SocketError
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Success | 0 | Uma operação de socket foi concluída com sucesso. |
| SocketError | -1 | Ocorreu um erro de socket não especificado. |
| Interrupted | 10004 | Uma chamada de socket bloqueante foi cancelada. |
| AccessDenied | 10013 | O acesso a um socket foi negado. |
| Fault | 10014 | Um endereço de ponteiro inválido foi detectado. |
| InvalidArgument | 10022 | Um argumento inválido foi fornecido. |
| TooManyOpenSockets | 10024 | Existem muitos sockets abertos no provedor de sockets subjacente. |
| WouldBlock | 10035 | Uma operação não pode ser concluída imediatamente em um socket não bloqueante. |
| InProgress | 10036 | Uma operação bloqueante está em andamento. |
| AlreadyInProgress | 10037 | Um socket não bloqueante já tem uma operação em execução. |
| NotSocket | 10038 | Uma tentativa de chamar uma operação de socket em um não-socket. |
| DestinationAddressRequired | 10039 | Um endereço necessário foi omitido de uma operação de socket. |
| MessageSize | 10040 | Um datagrama é muito longo. |
| ProtocolType | 10041 | Um tipo de protocolo não é suportado por este socket. |
| ProtocolOption | 10042 | Uma opção ou nível desconhecido, inválido ou não suportado foi usado. |
| ProtocolNotSupported | 10043 | Um protocolo não está implementado ou não está configurado. |
| SocketNotSupported | 10044 | Uma família de endereços não suporta o socket especificado. |
| OperationNotSupported | 10045 | Uma família de protocolos não suporta uma família de endereços. |
| ProtocolFamilyNotSupported | 10046 | Uma família de protocolos não está implementada ou não está configurada. |
| AddressFamilyNotSupported | 10047 | A família de endereços especificada não é suportada. |
| AddressAlreadyInUse | 10048 | Um endereço pode ser usado apenas uma vez. |
| AddressNotAvailable | 10049 | O endereço IP selecionado não é válido neste contexto. |
| NetworkDown | 10050 | A rede não está disponível. |
| NetworkUnreachable | 10051 | Nenhuma rota para o host remoto existe. |
| NetworkReset | 10052 | Um aplicativo tentou definir 'Keep-Alive' em uma conexão que já expirou. |
| ConnectionAborted | 10053 | Uma conexão foi abortada. |
| ConnectionReset | 10054 | Uma conexão foi reiniciada por um par remoto. |
| NoBufferSpaceAvailable | 10055 | Nenhum espaço de buffer livre está disponível para uma operação de socket. |
| IsConnected | 10056 | Um socket já está conectado. |
| NotConnected | 10057 | Um aplicativo tentou enviar ou receber dados, e um socket não está conectado. |
| Shutdown | 10058 | Uma solicitação para enviar ou receber dados é proibida porque o socket já foi fechado. |
| TimedOut | 10060 | Uma tentativa de conexão expirou, ou um host conectado não respondeu. |
| ConnectionRefused | 10061 | Um host remoto está recusando ativamente uma conexão. |
| HostDown | 10064 | Uma operação falhou porque um host remoto está inativo. |
| HostUnreachable | 10065 | Nenhuma rota de rede para o host especificado existe. |
| ProcessLimit | 10067 | Muitos processos estão usando o provedor de sockets subjacente. |
| SystemNotReady | 10091 | Um subsistema de rede está indisponível. |
| VersionNotSupported | 10092 | Uma versão do provedor de sockets subjacente está fora do intervalo. |
| NotInitialized | 10093 | O provedor de sockets subjacente não está inicializado. |
| Disconnecting | 10101 | Um desligamento gracioso está em andamento. |
| TypeNotFound | 10109 | A classe especificada não foi encontrada. |
| HostNotFound | 11001 | O host especificado é desconhecido. |
| TryAgain | 11002 | Um nome de host não pode ser resolvido. |
| NoRecovery | 11003 | Um erro é irrecuperável ou um banco de dados solicitado não pode ser localizado. |
| NoData | 11004 | Um nome ou endereço IP solicitado não foi encontrado no servidor de nomes. |

## Veja Também

* Namespace [System::Net::Sockets](../)
* Bibliotheca [Aspose.Slides](../../)