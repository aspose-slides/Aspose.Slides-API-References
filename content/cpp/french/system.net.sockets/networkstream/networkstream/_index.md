---
title: NetworkStream()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 170
url: /fr/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Le socket utilisé pour l'envoi et la réception de données. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Le socket utilisé pour l'envoi et la réception de données. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Spécifie le type d'accès attribué à l'instance sur le socket spécifié. |
| ownsSocket | **bool** | Valeur indiquant si l'instance actuelle prend possession du socket spécifié lorsque la valeur est vraie. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Le socket utilisé pour l'envoi et la réception de données. |
| ownsSocket | **bool** | Valeur indiquant si l'instance actuelle prend possession du socket spécifié lorsque la valeur est vraie. |

## Voir aussi

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Socket](../../socket/)
* Classe [NetworkStream](../)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)