---
title: ReceiveFrom()
second_title: Справка по API Aspose.Slides для C++
description: Получает данные от указанного конечного узла и записывает их в указанный массив байтов.
type: docs
weight: 690
url: /ru/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| size | **int32_t** | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| size | **int32_t** | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| size | **int32_t** | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | [SocketFlags](../../socketflags/) | Поведение при получении. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Массив байтов, в который будут записаны полученные данные. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) метод


Получает данные от указанного конечного узла и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Удаленный конечный узел. |

### Возвращаемое значение

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)