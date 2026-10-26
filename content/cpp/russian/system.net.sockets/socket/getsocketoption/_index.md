---
title: GetSocketOption()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает значение, соответствующее указанному имени параметра.
type: docs
weight: 729
url: /ru/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) метод

Возвращает значение, соответствующее указанному имени параметра.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Уровень параметра сокета. |
| optionName | [SocketOptionName](../../socketoptionname/) | Имя параметра. |

### Возвращаемое значение

Значение, соответствующее указанному имени параметра.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) метод

Получает значение, соответствующее указанному имени параметра.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Уровень параметра сокета. |
| optionName | [SocketOptionName](../../socketoptionname/) | Имя параметра. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Выходной параметр, в который будет присвоено соответствующее значение. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) метод

Возвращает значение, соответствующее указанному имени параметра.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Уровень параметра сокета. |
| optionName | [SocketOptionName](../../socketoptionname/) | Имя параметра. |
| optionLength | **int32_t** | Длина параметра. |

### Возвращаемое значение

Значение, соответствующее указанному имени параметра.

## См. также

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Object](../../../system/object/)
* Класс [Socket](../)
* Пространство имён [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)