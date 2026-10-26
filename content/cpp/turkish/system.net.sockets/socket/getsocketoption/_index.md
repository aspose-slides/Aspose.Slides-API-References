---
title: GetSocketOption()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen seçenek adına karşılık gelen değeri döndürür.
type: docs
weight: 729
url: /tr/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) metodu


Belirtilen seçenek adının karşılık gelen değerini döndürür.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Soket seçenek seviyesi. |
| optionName | [SocketOptionName](../../socketoptionname/) | Seçenek adı. |

### Dönüş Değeri

Belirtilen seçenek adının karşılık gelen değeri.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) metodu


Belirtilen seçenek adının karşılık gelen değerini alır.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Soket seçenek seviyesi. |
| optionName | [SocketOptionName](../../socketoptionname/) | Seçenek adı. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Karşılık gelen değerin atanacağı çıkış parametresi. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) metodu


Belirtilen seçenek adının karşılık gelen değerini döndürür.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Soket seçenek seviyesi. |
| optionName | [SocketOptionName](../../socketoptionname/) | Seçenek adı. |
| optionLength | **int32_t** | Seçenek uzunluğu. |

### Dönüş Değeri

Belirtilen seçenek adının karşılık gelen değeri.

## Ayrıca Bakınız

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Socket](../)
* İsim Uzayı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)