---
title: EndReceive()
second_title: Aspose.Slides для C++: справочник API
description: Ожидает завершения указанной асинхронной операции получения.
type: docs
weight: 534
url: /ru/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) метод

Ожидает завершения указанной асинхронной операции получения.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию получения. |

### Возвращаемое значение

Количество полученных байтов.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) метод

Ожидает завершения указанной асинхронной операции получения.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию получения. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в котором будет присвоен код ошибки, если операция получения завершится с ошибкой. |

### Возвращаемое значение

Количество полученных байтов.

## Смотрите также

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)