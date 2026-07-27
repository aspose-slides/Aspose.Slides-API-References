---
title: SocketType
second_title: Referência da API Aspose.Slides para C++
description: Enumera os tipos de socket.
type: docs
weight: 131
url: /pt/system.net.sockets/sockettype/
---
## enum SocketType

Enumera os tipos de socket.

```cpp
enum class SocketType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Stream | 1 | O tipo que suporta fluxos de bytes confiáveis, bidirecionais, baseados em conexão, sem duplicação de dados e sem preservação de limites. |
| Dgram | 2 | O tipo que suporta datagramas, que são mensagens sem conexão, não confiáveis, de comprimento máximo fixo. |
| Raw | 3 | O tipo que permite acesso ao protocolo de transporte subjacente. |
| Rdm | 4 | O tipo que suporta mensagens sem conexão, orientadas a mensagens, entregues de forma confiável, e preserva os limites das mensagens nos dados. |
| Seqpacket | 5 | O tipo que fornece transferência bidirecional, orientada a conexão e confiável de fluxos de bytes ordenados através de uma rede. |
| Unknown | n/a | Um tipo desconhecido. |

## Veja também

* Namespace [System::Net::Sockets](../)
* Biblioteca [Aspose.Slides](../../)