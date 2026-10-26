---
title: Receive()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um datagrama enviado por um servidor.
type: docs
weight: 92
url: /pt/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) método

Retorna um datagrama enviado por um servidor.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Um [IPEndPoint](../../../system.net/ipendpoint/) que representa o host remoto de onde os dados foram enviados. |

### Valor de retorno

Um array de bytes onde os dados recebidos serão atribuídos.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)