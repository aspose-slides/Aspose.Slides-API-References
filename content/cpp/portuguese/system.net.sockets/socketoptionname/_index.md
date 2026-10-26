---
title: SocketOptionName
second_title: Referência da API Aspose.Slides para C++
description: Define nomes de opções de socket para a classe Socket.
type: docs
weight: 248
url: /pt/system.net.sockets/socketoptionname/
---
## SocketOptionName enum

Define os nomes das opções de socket para a classe [Socket](../socket/).

```cpp
enum class SocketOptionName
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Debug | 1 | Registra informações de depuração. |
| AcceptConnection | 2 | Indica se um socket está ouvindo por uma conexão entrante. |
| ReuseAddress | 4 | Indica se um socket pode ser ligado ao endereço que já está em uso. |
| KeepAlive | 8 | Habilita os pacotes 'Keep-Alive' para uma conexão de socket. |
| DontRoute | 16 | Indica se um pacote é enviado diretamente aos endereços da interface. |
| Broadcast | 32 | Indica se um socket pode enviar mensagens de broadcast. |
| UseLoopback | 64 | Ignora o hardware quando possível. |
| Linger | 128 | O sistema bloqueará o processo na tentativa de fechamento até que seja possível transmitir os dados. |
| OutOfBandInline | 256 | Recebe dados fora de banda no fluxo normal de dados. |
| DontLinger | n/a | Indica se um socket será fechado sem linger. |
| ExclusiveAddressUse | n/a | Um socket usará o endereço vinculado exclusivamente. |
| SendBuffer | 4097 | Especifica o tamanho do buffer de envio. |
| ReceiveBuffer | 4098 | Especifica o tamanho do buffer de recebimento. |
| SendLowWater | 4099 | Especifica a quantidade mínima de dados para as operações de envio. |
| ReceiveLowWater | 4100 | Especifica a quantidade mínima de dados para as operações de recebimento. |
| SendTimeout | 4101 | Especifica o tempo limite para as operações síncronas de envio. |
| ReceiveTimeout | 4102 | Especifica o tempo limite para as operações síncronas de recebimento. |
| Error | 4103 | Retorna o status de erro e limpa. |
| Type | 4104 | Retorna um tipo de socket. |
| ReuseUnicastPort | 12295 | Indica se o sistema deve adiar a alocação de portas efêmeras para as conexões de saída. |
| MaxConnections | 2147483647 | Esta opção não é suportada. Era usada para especificar o comprimento máximo da fila de escuta. |
| IPOptions | 1 | Especifica a opção IP que deve ser inserida nos datagramas de saída. |
| HeaderIncluded | 2 | O cabeçalho está incluído nos datagramas de saída. |
| TypeOfService | 3 | Altera o tipo de campo de serviço do cabeçalho IP. |
| IpTimeToLive | 4 | O tempo de vida (TTL) do IP. |
| MulticastInterface | 9 | Define a interface para os pacotes multicast de saída. |
| MulticastTimeToLive | 10 | O tempo de vida (TTL) do multicast IP. |
| MulticastLoopback | 11 | O loopback do multicast IP. |
| AddMembership | 12 | Adiciona uma associação a um grupo IP. |
| DropMembership | 13 | Remove uma associação a um grupo IP. |
| DontFragment | 14 | Não fragmenta os datagramas IP. |
| AddSourceMembership | 15 | Ingressa no grupo/fonte IP. |
| DropSourceMembership | 16 | Remove o grupo/fonte IP. |
| BlockSource | 17 | Bloqueia o grupo/fonte IP. |
| UnblockSource | 18 | Desbloqueia o grupo/fonte IP. |
| PacketInformation | 19 | Recebe informações de pacote para IPv4. |
| HopLimit | 21 | Entrega um inteiro contendo a contagem HOP do pacote. |
| IPProtectionLevel | 23 | Habilita a restrição de um socket IPv6 ao escopo especificado. |
| IPv6Only | 27 | O socket está restrito a enviar e receber apenas pacotes IPv6. |
| NoDelay | 1 | Desabilita o algoritmo de Nagle para a coalescência dos pacotes de envio. |
| BsdUrgent | 2 | Usa os dados urgentes conforme definido na RFC-1222. |
| Expedited | 2 | Usa os dados expedited conforme definido na RFC-1222. |
| NoChecksum | 1 | Envia os datagramas UDP com a soma de verificação definida como zero. |
| ChecksumCoverage | 20 | Define ou obtém a cobertura da soma de verificação UDP. |
| UpdateAcceptContext | 28683 | Atualiza um socket cliente com as mesmas propriedades de um socket de escuta. |
| UpdateConnectContext | 28688 | Atualiza um socket cliente com as mesmas propriedades de um socket de escuta. |

## Ver também

* Namespace [System::Net::Sockets](../)
* Biblioteca [Aspose.Slides](../../)