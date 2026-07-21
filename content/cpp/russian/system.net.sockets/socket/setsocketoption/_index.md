---
title: SetSocketOption()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает указанную опцию сокета в указанное значение.
type: docs
weight: 716
url: /ru/system.net.sockets/socket/setsocketoption/
---
## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) метод

Устанавливает указанную опцию сокета в указанное значение.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Уровень опции сокета. |
| optionName | [SocketOptionName](../../socketoptionname/) | Наименование опции, которую необходимо обновить. |
| optionValue | **int32_t** | Значение, которое должно быть установлено для указанной опции. |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) метод


Устанавливает указанную опцию сокета в указанное значение.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Уровень опции сокета. |
| optionName | [SocketOptionName](../../socketoptionname/) | Наименование опции, которую необходимо обновить. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Значение, которое должно быть установлено для указанной опции. |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, bool) метод


Устанавливает указанную опцию сокета в указанное значение.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, bool optionValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Уровень опции сокета. |
| optionName | [SocketOptionName](../../socketoptionname/) | Наименование опции, которую необходимо обновить. |
| optionValue | **bool** | Значение, которое должно быть установлено для указанной опции. |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) метод


Устанавливает указанную опцию сокета в указанное значение.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::SharedPtr<Object> optionValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Уровень опции сокета. |
| optionName | [SocketOptionName](../../socketoptionname/) | Наименование опции, которую необходимо обновить. |
| optionValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Значение, которое должно быть установлено для указанной опции. |

## См. также

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [Object](../../../system/object/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)