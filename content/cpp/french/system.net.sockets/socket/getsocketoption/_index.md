---
title: GetSocketOption()
second_title: Aspose.Slides pour C++ Référence API
description: Renvoie la valeur qui correspond au nom d'option spécifié.
type: docs
weight: 729
url: /fr/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) méthode


Renvoie la valeur qui correspond au nom d'option spécifié.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Le niveau d'option du socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | Le nom de l'option. |

### Valeur de retour

La valeur qui correspond au nom d'option spécifié.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) méthode


Obtient la valeur qui correspond au nom d'option spécifié.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Le niveau d'option du socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | Le nom de l'option. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le paramètre de sortie où la valeur correspondante sera affectée. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) méthode


Renvoie la valeur qui correspond au nom d'option spécifié.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Le niveau d'option du socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | Le nom de l'option. |
| optionLength | **int32_t** | La longueur de l'option. |

### Valeur de retour

La valeur qui correspond au nom d'option spécifié.

## Voir aussi

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)