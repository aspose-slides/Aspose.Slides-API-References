---
title: IOControlCode
second_title: Referência da API Aspose.Slides para C++
description: Enumera os códigos de controle IO.
type: docs
weight: 157
url: /pt/system.net.sockets/iocontrolcode/
---
## IOControlCode enum

Enumera os códigos de controle [IO](../../system.io/).

```cpp
enum class IOControlCode : int64_t
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| AsyncIO | -2147195267 | Habilita ou desabilita o modo assíncrono de I/O do socket. |
| NonBlockingIO | -2147195266 | Marca o socket como não bloqueante. |
| DataToRead | 1074030207 | Retorna o número de bytes disponíveis para leitura. |
| OobDataRead | 1074033415 | Retorna informações sobre dados fora da banda que aguardam ser recebidos. |
| AssociateHandle | -2013265919 | Associa este socket ao identificador especificado de uma interface companheira. |
| EnableCircularQueuing | 671088642 | Substitui o datagrama enfileirado mais antigo por um novo quando as filas de mensagens recebidas estão cheias. |
| Flush | 671088644 | Descarta o conteúdo atual da fila de envio associada a este socket. |
| GetBroadcastAddress | 1207959557 | Retorna uma estrutura SOCKADDR que contém o endereço de broadcast para a família de endereços do socket atual. |
| GetExtensionFunctionPointer | -939524090 | Recupera um ponteiro para a função de extensão especificada suportada pelo provedor de serviço associado. |
| GetQos | -939524089 | Recupera a estrutura QOS associada ao socket. |
| GetGroupQos | -939524088 | Retorna os atributos QOS para o grupo de sockets. |
| MultipointLoopback | -2013265911 | Controla se os dados enviados por um aplicativo no computador local (não necessariamente pelo mesmo socket) em uma sessão multicast serão recebidos por um socket unido ao grupo de destino multicast na interface de loopback. |
| MulticastScope | -2013265910 | Controla o número de vezes que um pacote multicast pode ser encaminhado por um roteador, também conhecido como TTL ou contagem de saltos. |
| SetQos | -2013265909 | Define os atributos QOS para o socket. |
| SetGroupQos | -2013265908 | Define os atributos QOS para o grupo de sockets. |
| TranslateHandle | -939524083 | Retorna um identificador para o socket que é válido no contexto de uma interface companheira. |
| RoutingInterfaceQuery | -939524076 | Retorna os endereços de interface que podem ser usados para conectar ao endereço remoto especificado. |
| RoutingInterfaceChange | -2013265899 | Habilita o recebimento de notificação quando a interface local usada para acessar um ponto remoto muda. |
| AddressListQuery | 1207959574 | Retorna a lista das interfaces locais às quais o socket pode ser associado. |
| AddressListChange | 671088663 | Habilita o recebimento de notificação quando a lista das interfaces locais para a família de protocolos do socket mudar. |
| QueryTargetPnpHandle | 1207959576 | Recupera o identificador SOCKET do provedor subjacente. |
| NamespaceChange | -2013265895 | Controla se o socket recebe notificação quando uma consulta de namespace se torna inválida. |
| AddressListSort | -939524071 | Ordena uma lista de endereços de destino IPv6 e IPv4 para determinar o melhor endereço disponível para estabelecer uma conexão. |
| ReceiveAll | -1744830463 | Habilita o recebimento de todos os pacotes IPv4 na rede. |
| ReceiveAllMulticast | -1744830462 | Habilita o recebimento de todos os pacotes IPv4 multicast na rede. |
| ReceiveAllIgmpMulticast | -1744830461 | Habilita o recebimento de todos os pacotes IGMP na rede. |
| KeepAliveValues | -1744830460 | Controla o envio de pacotes TCP keep-alive e o intervalo entre envios. |
| AbsorbRouterAlert | -1744830459 | Este valor é igual à constante 'SIO_ABSORB_RTRALERT' do Winsock 2. |
| UnicastInterface | -1744830458 | Define a interface usada para os pacotes unicast de saída. |
| LimitBroadcasts | -1744830457 | Este valor é igual à constante 'SIO_LIMIT_BROADCASTS' do Winsock 2. |
| BindToInterface | -1744830456 | Associa o socket a um índice de interface especificado. |
| MulticastInterface | -1744830455 | Define a interface usada para os pacotes multicast de saída. |
| AddMulticastGroupOnInterface | -1744830454 | Ingressa em um grupo multicast usando uma interface identificada pelo seu índice. |
| DeleteMulticastGroupFromInterface | -1744830453 | Remove o socket de um grupo multicast. |

## Veja Também

* Espaço de nomes [System::Net::Sockets](../)
* Biblioteca [Aspose.Slides](../../)