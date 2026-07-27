---
title: SocketFlags
second_title: Referência da API Aspose.Slides for C++
description: Fornece valores constantes para as mensagens de socket.
type: docs
weight: 222
url: /pt/system.net.sockets/socketflags/
---
## SocketFlags enum


Fornece valores constantes para as mensagens de socket.

```cpp
enum class SocketFlags
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Não há flags usadas nesta chamada. |
| OutOfBand | 1 | Os dados fora da banda estão sendo processados. |
| Peek | 2 | Visualizar uma mensagem recebida. |
| DontRoute | 4 | Enviar uma mensagem sem usar tabelas de roteamento. |
| Truncated | 256 | Uma mensagem é grande demais para caber no buffer especificado. Ela foi truncada. |
| ControlDataTruncated | 512 | Os dados de controle são maiores que 64 KB e não cabem no buffer interno. Eles foram truncados. |
| Broadcast | 1024 | Um pacote de broadcast. |
| Multicast | 2048 | Um pacote de multicast. |
| Partial | 32768 | Uma mensagem enviada ou recebida parcialmente. |

## Veja Também

* Namespace [System::Net::Sockets](../)
* Biblioteca [Aspose.Slides](../../)