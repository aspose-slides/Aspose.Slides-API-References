---
title: GetSocketOption()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de waarde die overeenkomt met de opgegeven optienaam.
type: docs
weight: 729
url: /nl/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) methode


Retourneert de waarde die overeenkomt met de opgegeven optienaam.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Het socket-optieniveau. |
| optionName | [SocketOptionName](../../socketoptionname/) | De optienaam. |

### Retourwaarde

De waarde die overeenkomt met de opgegeven optienaam.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) methode


Haalt de waarde op die overeenkomt met de opgegeven optienaam.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Het socket-optieniveau. |
| optionName | [SocketOptionName](../../socketoptionname/) | De optienaam. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De uitvoerparameter waar de overeenkomstige waarde aan wordt toegewezen. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) methode


Retourneert de waarde die overeenkomt met de opgegeven optienaam.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Het socket-optieniveau. |
| optionName | [SocketOptionName](../../socketoptionname/) | De optienaam. |
| optionLength | **int32_t** | De optie-lengte. |

### Retourwaarde

De waarde die overeenkomt met de opgegeven optienaam.

## Zie ook

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)