---
title: GetSocketOption()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert zurück, der dem angegebenen Optionsnamen entspricht.
type: docs
weight: 729
url: /de/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) Methode

Gibt den Wert zurück, der dem angegebenen Optionsnamen entspricht.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Die Socket-Optionsebene. |
| optionName | [SocketOptionName](../../socketoptionname/) | Der Optionsname. |

### Rückgabewert

Der Wert, der dem angegebenen Optionsnamen entspricht.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) Methode

Ruft den Wert ab, der dem angegebenen Optionsnamen entspricht.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Die Socket-Optionsebene. |
| optionName | [SocketOptionName](../../socketoptionname/) | Der Optionsname. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Der Ausgabeparameter, dem der entsprechende Wert zugewiesen wird. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) Methode

Gibt den Wert zurück, der dem angegebenen Optionsnamen entspricht.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Die Socket-Optionsebene. |
| optionName | [SocketOptionName](../../socketoptionname/) | Der Optionsname. |
| optionLength | **int32_t** | Die Optionslänge. |

### Rückgabewert

Der Wert, der dem angegebenen Optionsnamen entspricht.

## Siehe auch

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Socket](../)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)