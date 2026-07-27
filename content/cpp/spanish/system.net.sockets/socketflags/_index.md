---
title: SocketFlags
second_title: Referencia de la API de Aspose.Slides para C++
description: Proporciona valores constantes para los mensajes de socket.
type: docs
weight: 222
url: /es/system.net.sockets/socketflags/
---
## SocketFlags enumeración

Proporciona valores constantes para los mensajes de socket.

```cpp
enum class SocketFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | No se utilizan banderas para esta llamada. |
| OutOfBand | 1 | Se están procesando los datos fuera de banda. |
| Peek | 2 | Echar un vistazo a un mensaje entrante. |
| DontRoute | 4 | Enviar un mensaje sin usar tablas de enrutamiento. |
| Truncated | 256 | Un mensaje es demasiado grande para caber en el búfer especificado. Ha sido truncado. |
| ControlDataTruncated | 512 | Los datos de control son mayores de 64 KB y no caben en el búfer interno. Han sido truncados. |
| Broadcast | 1024 | Un paquete de transmisión. |
| Multicast | 2048 | Un paquete multidifusión. |
| Partial | 32768 | Un mensaje enviado o recibido parcialmente. |

## Ver también

* Espacio de nombres [System::Net::Sockets](../)
* Biblioteca [Aspose.Slides](../../)