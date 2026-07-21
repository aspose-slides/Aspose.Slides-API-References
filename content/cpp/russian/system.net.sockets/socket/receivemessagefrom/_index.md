---
title: ReceiveMessageFrom()
second_title: Справочник API Aspose.Slides для C++
description: Получает данные от указанного конечного узла и записывает их в указанный массив байтов.
type: docs
weight: 677
url: /ru/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов, которые необходимо получить и которые будут записаны в указанный массив байтов, начиная с индекса «offset». |
| socketFlags | [SocketFlags](../../socketflags/)\& | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удалённый конечный узел. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Выходной параметр, в который будет записана информация о пакете. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов, которые необходимо получить и которые будут записаны в указанный массив байтов, начиная с индекса «offset». |
| socketFlags | [SocketFlags](../../socketflags/)\& | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удалённый конечный узел. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Выходной параметр, в который будет записана информация о пакете. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов, которые необходимо получить и которые будут записаны в указанный массив байтов, начиная с индекса «offset». |
| socketFlags | [SocketFlags](../../socketflags/)\& | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удалённый конечный узел. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Выходной параметр, в который будет записана информация о пакете. |

### Возвращаемое значение

Количество полученных байтов.

## Смотрите также

* Перечисление [SocketFlags](../../socketflags/)
* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [EndPoint](../../../system.net/endpoint/)
* Класс [IPPacketInformation](../../ippacketinformation/)
* Класс [Socket](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)