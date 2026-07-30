---
title: ReceiveMessageFrom()
second_title: Riferimento API di Aspose.Slides per C++
description: Riceve dati dal punto finale specificato e li scrive nell'array di byte specificato.
type: docs
weight: 677
url: /it/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metodo


Riceve dati dal punto finale specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Il punto finale remoto. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Il parametro di output dove verranno assegnate le informazioni sul pacchetto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metodo


Riceve dati dal punto finale specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Il punto finale remoto. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Il parametro di output dove verranno assegnate le informazioni sul pacchetto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metodo


Riceve dati dal punto finale specificato e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | L'array di byte dove verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Il punto finale remoto. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Il parametro di output dove verranno assegnate le informazioni sul pacchetto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Vedi anche

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [EndPoint](../../../system.net/endpoint/)
* Classe [IPPacketInformation](../../ippacketinformation/)
* Classe [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)