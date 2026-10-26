---
title: BeginConnect()
second_title: Aspose.Slides для C++ справочник API
description: Инициирует асинхронную операцию подключения.
type: docs
weight: 573
url: /ru/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию подключения.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Удалённая конечная точка. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван после завершения операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции подключения. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию подключения.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию подключения.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | [String](../../../system/string/) | Имя удалённого хоста. |
| port | **int32_t** | Номер порта удалённого хоста. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван после завершения операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции подключения. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию подключения.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию подключения.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | IP-адрес удалённого хоста. |
| port | **int32_t** | Номер порта удалённого хоста. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван после завершения операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции подключения. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию подключения.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию подключения.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP-адреса удалённого хоста. |
| port | **int32_t** | Номер порта удалённого хоста. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван после завершения операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции подключения. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию подключения.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Типовое определение [AsyncCallback](../../../system/asynccallback/)
* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [EndPoint](../../../system.net/endpoint/)
* Класс [Object](../../../system/object/)
* Класс [Socket](../)
* Класс [String](../../../system/string/)
* Класс [IPAddress](../../../system.net/ipaddress/)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)