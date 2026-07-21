---
title: EndGetHostByName()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает завершения указанной асинхронной операции по созданию нового экземпляра IPHostEntry-class.
type: docs
weight: 66
url: /ru/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) метод

Ожидает завершения указанной асинхронной операции по созданию нового экземпляра IPHostEntry-class.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию. |

### Возвращаемое значение

Новый созданный экземпляр IPHostEntry-class.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPHostEntry](../../iphostentry/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Dns](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)