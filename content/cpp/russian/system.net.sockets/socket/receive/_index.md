---
title: Receive()
second_title: Справочное руководство API Aspose.Slides для C++
description: Получает данные из сокета и записывает их в указанный массив байтов.
type: docs
weight: 664
url: /ru/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| size | **int32_t** | Количество байтов для получения. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| size | **int32_t** | Количество байтов для получения. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| size | **int32_t** | Количество байтов для получения. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Массив байтов, в который будут записаны полученные данные. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов, которое будет получено и записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов, которое будет получено и записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов, которое будет получено и записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов, которое будет получено и записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в который будет записан код ошибки, если операция получения завершится неудачей. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов, которое будет получено и записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в который будет записан код ошибки, если операция получения завершится неудачей. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) метод


Принимает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов, которое будет получено и записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в который будет записан код ошибки, если операция получения завершится неудачей. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) метод


Принимает данные из сокета и записывает их в указанные массивы байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Массивы байтов, в которые будут записаны полученные данные. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) метод


Принимает данные из сокета и записывает их в указанные массивы байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Массивы байтов, в которые будут записаны полученные данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |

### Возвращаемое значение

Количество полученных байт.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) метод


Принимает данные из сокета и записывает их в указанные массивы байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Массивы байтов, в которые будут записаны полученные данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в который будет записан код ошибки, если операция получения завершится неудачей. |

### Возвращаемое значение

Количество полученных байт.

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