---
title: SocketError
second_title: Referencia de API de Aspose.Slides para C++
description: Enumera los tipos de error de socket.
type: docs
weight: 209
url: /es/system.net.sockets/socketerror/
---
## SocketError enum

Enumera los tipos de error de socket.

```cpp
enum class SocketError
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Success | 0 | Una operación de socket se completó con éxito. |
| SocketError | -1 | Ocurrió un error de socket no especificado. |
| Interrupted | 10004 | Se cancela una llamada de socket bloqueante. |
| AccessDenied | 10013 | El acceso a un socket es denegado. |
| Fault | 10014 | Se detectó una dirección de puntero no válida. |
| InvalidArgument | 10022 | Se proporcionó un argumento no válido. |
| TooManyOpenSockets | 10024 | Hay demasiados sockets abiertos en el proveedor subyacente. |
| WouldBlock | 10035 | No se puede completar inmediatamente una operación en un socket no bloqueante. |
| InProgress | 10036 | Una operación bloqueante está en progreso. |
| AlreadyInProgress | 10037 | Un socket no bloqueante ya tiene una operación en ejecución. |
| NotSocket | 10038 | Se intentó llamar a una operación de socket sobre un no-socket. |
| DestinationAddressRequired | 10039 | Falta una dirección requerida en una operación de socket. |
| MessageSize | 10040 | Un datagrama es demasiado largo. |
| ProtocolType | 10041 | Un tipo de protocolo no es compatible con este socket. |
| ProtocolOption | 10042 | Se usa una opción o nivel desconocido, inválido o no soportado. |
| ProtocolNotSupported | 10043 | Un protocolo no está implementado o no está configurado. |
| SocketNotSupported | 10044 | Una familia de direcciones no soporta el socket especificado. |
| OperationNotSupported | 10045 | Una familia de protocolos no soporta una familia de direcciones. |
| ProtocolFamilyNotSupported | 10046 | Una familia de protocolos no está implementada o no está configurada. |
| AddressFamilyNotSupported | 10047 | La familia de direcciones especificada no es compatible. |
| AddressAlreadyInUse | 10048 | Una dirección solo puede usarse una vez. |
| AddressNotAvailable | 10049 | La dirección IP seleccionada no es válida en este contexto. |
| NetworkDown | 10050 | La red no está disponible. |
| NetworkUnreachable | 10051 | No existe ruta al host remoto. |
| NetworkReset | 10052 | Una aplicación intentó establecer 'Keep-Alive' en una conexión que ya había expirado. |
| ConnectionAborted | 10053 | Una conexión es abortada. |
| ConnectionReset | 10054 | Una conexión es reiniciada por un par remoto. |
| NoBufferSpaceAvailable | 10055 | No hay espacio de buffer libre disponible para una operación de socket. |
| IsConnected | 10056 | Un socket ya está conectado. |
| NotConnected | 10057 | Una aplicación intentó enviar o recibir datos, y el socket no está conectado. |
| Shutdown | 10058 | Una solicitud de envío o recepción de datos está prohibida porque el socket ya fue cerrado. |
| TimedOut | 10060 | Un intento de conexión expiró, o un host conectado no respondió. |
| ConnectionRefused | 10061 | Un host remoto está rechazando activamente la conexión. |
| HostDown | 10064 | Una operación falló porque un host remoto está inactivo. |
| HostUnreachable | 10065 | No existe ruta de red al host especificado. |
| ProcessLimit | 10067 | Demasiados procesos están usando el proveedor subyacente de sockets. |
| SystemNotReady | 10091 | Un subsistema de red no está disponible. |
| VersionNotSupported | 10092 | Una versión del proveedor subyacente de sockets está fuera de rango. |
| NotInitialized | 10093 | El proveedor subyacente de sockets no está inicializado. |
| Disconnecting | 10101 | Se está realizando un apagado ordenado. |
| TypeNotFound | 10109 | La clase especificada no se encuentra. |
| HostNotFound | 11001 | El host especificado es desconocido. |
| TryAgain | 11002 | No se puede resolver el nombre de un host. |
| NoRecovery | 11003 | Un error no es recuperable o la base de datos solicitada no se puede localizar. |
| NoData | 11004 | Un nombre o dirección IP solicitado no se encuentra en el servidor de nombres. |

## Ver también

* Espacio de nombres [System::Net::Sockets](../)
* Biblioteca [Aspose.Slides](../../)