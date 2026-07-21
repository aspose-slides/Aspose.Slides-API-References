---
title: BeginAcceptSocket()
second_title: Aspose.Slides для C++ справочника API
description: Инициирует асинхронную операцию приёма.
type: docs
weight: 144
url: /ru/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию приёма.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван после завершения операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Данные, предоставленные пользователем, используемые для однозначной идентификации каждой асинхронной операции подключения. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию приёма.

## Смотрите также

* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Тип-определение [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Object](../../../system/object/)
* Класс [TcpListener](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)