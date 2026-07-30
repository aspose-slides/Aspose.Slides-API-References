---
title: NetworkStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 170
url: /it/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) costruttore

Crea una nuova istanza.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Il socket utilizzato per inviare e ricevere dati. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) costruttore

Crea una nuova istanza.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Il socket utilizzato per inviare e ricevere dati. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Specifica il tipo di accesso fornito all'istanza sul socket specificato. |
| ownsSocket | **bool** | Un valore che indica se l'istanza corrente prende possesso del socket specificato quando il valore è true. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) costruttore

Crea una nuova istanza.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Il socket utilizzato per inviare e ricevere dati. |
| ownsSocket | **bool** | Un valore che indica se l'istanza corrente prende possesso del socket specificato quando il valore è true. |

## Vedi anche

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Socket](../../socket/)
* Classe [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)