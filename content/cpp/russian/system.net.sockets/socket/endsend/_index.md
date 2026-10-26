---
title: EndSend()
second_title: Aspose.Slides для C++ API Reference
description: Ожидает завершения указанной асинхронной операции отправки.
type: docs
weight: 508
url: /ru/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) method

Ожидает завершения указанной асинхронной операции отправки.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию отправки. |

### Return Value

Количество отправленных байтов.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) method

Ожидает завершения указанной асинхронной операции отправки.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию отправки. |
| errorCode | [SocketError](../../socketerror/)\& | Выходной параметр, в который будет записан код ошибки, если операция отправки завершится с ошибкой. |

### Return Value

Количество отправленных байтов.

## See Also

* Перечисление [SocketError](../../socketerror/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Socket](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)