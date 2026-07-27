---
title: SocketType
second_title: Referencia de la API de Aspose.Slides para C++
description: Enumera los tipos de socket.
type: docs
weight: 131
url: /es/system.net.sockets/sockettype/
---
## SocketType enum

Enumera los tipos de socket.

```cpp
enum class SocketType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Stream | 1 | El tipo que admite flujos de bytes confiables, bidireccionales y basados en conexión, sin duplicación de datos y sin preservación de los límites. |
| Dgram | 2 | El tipo que admite datagramas, que son mensajes sin conexión, poco confiables, de longitud máxima fija. |
| Raw | 3 | El tipo que permite el acceso al protocolo de transporte subyacente. |
| Rdm | 4 | El tipo que admite mensajes sin conexión, orientados a mensajes, entregados de forma fiable, y que preserva los límites de los mensajes en los datos. |
| Seqpacket | 5 | El tipo que proporciona transferencia bidireccional y fiable, orientada a conexión, de flujos de bytes ordenados a través de una red. |
| Unknown | n/a | Un tipo desconocido. |

## Ver también

* Espacio de nombres [System::Net::Sockets](../)
* Biblioteca [Aspose.Slides](../../)