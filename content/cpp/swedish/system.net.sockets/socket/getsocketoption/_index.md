---
title: GetSocketOption()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar värdet som motsvarar det angivna alternativnamnet.
type: docs
weight: 729
url: /sv/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) metod

Returnerar värdet som motsvarar det angivna alternativnamnet.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Socket-alternativnivån. |
| optionName | [SocketOptionName](../../socketoptionname/) | Alternativnamnet. |

### Returvärde

Värdet som motsvarar det angivna alternativnamnet.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) metod

Hämtar värdet som motsvarar det angivna alternativnamnet.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Socket-alternativnivån. |
| optionName | [SocketOptionName](../../socketoptionname/) | Alternativnamnet. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Utdataparametern där det motsvarande värdet kommer att tilldelas. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) metod

Returnerar värdet som motsvarar det angivna alternativnamnet.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Socket-alternativnivån. |
| optionName | [SocketOptionName](../../socketoptionname/) | Alternativnamnet. |
| optionLength | **int32_t** | Alternativlängden. |

### Returvärde

Värdet som motsvarar det angivna alternativnamnet.

## Se även

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Object](../../../system/object/)
* Klass [Socket](../)
* Namnrum [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)