---
title: Send()
second_title: Справочник API Aspose.Slides для C++
description: Отправляет указанные данные в сокет.
type: docs
weight: 638
url: /ru/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Данные для отправки. |
| size | **int32_t** | Количество байтов из указанных данных, которые необходимо отправить. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Данные для отправки. |
| size | **int32_t** | Количество байтов из указанных данных, которые необходимо отправить. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Данные для отправки. |
| size | **int32_t** | Количество байтов из указанных данных, которые необходимо отправить. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Данные для отправки. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Данные для отправки. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Данные для отправки. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::ArrayPtr\<uint8_t\>) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Данные для отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Данные для отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) метод


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Данные для отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Коллекция массивов байтов, из которых необходимо отправить данные. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Коллекция массивов байтов, из которых необходимо отправить данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Коллекция массивов байтов, из которых необходимо отправить данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в который будет записан код ошибки, если операция отправки завершится неудачно. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Данные для отправки. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов в указанном массиве, начиная с параметра «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Данные для отправки. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов в указанном массиве, начиная с параметра «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) метод


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Данные для отправки. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов в указанном массиве, начиная с параметра «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Данные для отправки. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов в указанном массиве, начиная с параметра «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в который будет записан код ошибки, если операция отправки завершится неудачно. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) метод


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Данные для отправки. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов в указанном массиве, начиная с параметра «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в который будет записан код ошибки, если операция отправки завершится неудачно. |

### Возвращаемое значение

Количество отправленных байтов.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) метод


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Данные для отправки. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов в указанном массиве, начиная с параметра «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение отправки. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в который будет записан код ошибки, если операция отправки завершится неудачно. |

### Возвращаемое значение

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)