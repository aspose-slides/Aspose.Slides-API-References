---
title: NetworkStream()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir örnek oluşturur.
type: docs
weight: 170
url: /tr/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Veri gönderme ve alımında kullanılan socket. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Veri gönderme ve alımında kullanılan socket. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Belirtilen socket üzerinde örneğe verilen erişim türünü belirtir. |
| ownsSocket | **bool** | Değer doğru olduğunda, mevcut örneğin belirtilen socket üzerindeki sahipliği alıp almayacağını gösteren bir değer. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Veri gönderme ve alımında kullanılan socket. |
| ownsSocket | **bool** | Değer doğru olduğunda, mevcut örneğin belirtilen socket üzerindeki sahipliği alıp almayacağını gösteren bir değer. |

## Ayrıca Bakınız

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../../socket/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)