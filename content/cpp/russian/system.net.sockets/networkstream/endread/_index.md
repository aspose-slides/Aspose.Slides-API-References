---
title: EndRead()
second_title: Aspose.Slides для C++ справочник API
description: Ожидает завершения указанной асинхронной операции чтения.
type: docs
weight: 261
url: /ru/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) метод

Ожидает завершения указанной асинхронной операции чтения.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию чтения |

### Возвращаемое значение

Количество байтов, считанных во время операции чтения, представленной **asyncResult**

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [NetworkStream](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)