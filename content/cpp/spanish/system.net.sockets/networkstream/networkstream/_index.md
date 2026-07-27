---
title: NetworkStream()
second_title: Aspose.Slides para la referencia de la API de C++
description: Construye una nueva instancia.
type: docs
weight: 170
url: /es/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | El socket que se utiliza para enviar y recibir datos. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | El socket que se utiliza para enviar y recibir datos. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Especifica el tipo de acceso otorgado a la instancia sobre el socket especificado. |
| ownsSocket | **bool** | Un valor que indica si la instancia actual toma posesión del socket especificado cuando el valor es verdadero. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | El socket que se utiliza para enviar y recibir datos. |
| ownsSocket | **bool** | Un valor que indica si la instancia actual toma posesión del socket especificado cuando el valor es verdadero. |

## Ver también

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../../socket/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)