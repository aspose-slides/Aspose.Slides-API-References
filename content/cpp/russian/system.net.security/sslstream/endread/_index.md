---
title: EndRead()
second_title: Aspose.Slides для C++ справка API
description: Ожидает завершения указанной асинхронной операции чтения.
type: docs
weight: 430
url: /ru/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) метод

Ожидает завершения указанной асинхронной операции чтения.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию чтения |

### Возвращаемое значение

Количество байтов, считанных во время операции чтения, представленной **asyncResult**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [SslStream](../)
* Пространство имён [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)