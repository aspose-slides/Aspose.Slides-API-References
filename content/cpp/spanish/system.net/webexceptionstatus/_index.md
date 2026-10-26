---
title: WebExceptionStatus
second_title: Referencia de API de Aspose.Slides para C++
description: Enumera los códigos de estado de la clase WebException.
type: docs
weight: 651
url: /es/system.net/webexceptionstatus/
---
## WebExceptionStatus enum


Enumera los códigos de estado de la clase WebException.

```cpp
enum class WebExceptionStatus
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Success | 0 | No se produjeron errores. |
| NameResolutionFailure | 1 | El servicio de resolución de nombres no pudo resolver el nombre del host. |
| ConnectFailure | 2 | No se pudo contactar el punto de servicio remoto a nivel de transporte. |
| ReceiveFailure | 3 | No se recibió una respuesta completa del servidor remoto. |
| SendFailure | 4 | No se pudo enviar una solicitud completa al servidor remoto. |
| PipelineFailure | 5 | La solicitud era una solicitud en canalización y la conexión se cerró antes de que se recibiera la respuesta. |
| RequestCanceled | 6 | La solicitud fue cancelada o se produjo un error no clasificable. |
| ProtocolError | 7 | La respuesta recibida del servidor estaba completa pero indicaba un error a nivel de protocolo. |
| ConnectionClosed | 8 | La conexión se cerró prematuramente. |
| TrustFailure | 9 | No se pudo validar un certificado del servidor. |
| SecureChannelFailure | 10 | Se produjo un error al establecer una conexión usando SSL. |
| ServerProtocolViolation | 11 | La respuesta del servidor no era una respuesta HTTP válida. |
| KeepAliveFailure | 12 | La conexión para una solicitud que especifica la cabecera 'Keep-Alive' se cerró inesperadamente. |
| Pending | 13 | Una solicitud asíncrona interna está pendiente. |
| Timeout | 14 | No se recibió respuesta durante el período de tiempo de espera de una solicitud. |
| ProxyNameResolutionFailure | 15 | El servicio de resolución de nombres no pudo resolver el nombre del host del proxy. |
| UnknownError | 16 | Se ha producido una excepción de tipo desconocido. |
| MessageLengthLimitExceeded | 17 | Se recibió un mensaje que superó el límite especificado. |
| CacheEntryNotFound | 18 | No se encontró la entrada de caché especificada. |
| RequestProhibitedByCachePolicy | 19 | La solicitud no fue permitida por la política de caché. |
| RequestProhibitedByProxy | 20 | Esta solicitud no fue permitida por el proxy. |

## Ver también

* Espacio de nombres [System::Net](../)
* Biblioteca [Aspose.Slides](../../)