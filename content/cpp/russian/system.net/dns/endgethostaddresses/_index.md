---
title: EndGetHostAddresses()
second_title: Aspose.Slides для C++ справка по API
description: Ожидает, пока указанная асинхронная операция по созданию нового экземпляра IPHostEntry-class завершится.
type: docs
weight: 144
url: /ru/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) метод

Ожидает, пока указанная асинхронная операция по созданию нового экземпляра IPHostEntry-class завершится.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию. |

### Возвращаемое значение

Новый созданный экземпляр IPHostEntry-class.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPAddress](../../ipaddress/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Dns](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)