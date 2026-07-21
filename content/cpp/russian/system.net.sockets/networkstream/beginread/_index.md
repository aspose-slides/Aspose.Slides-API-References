---
title: BeginRead()
second_title: Aspose.Slides для C++ справочник API
description: Инициирует асинхронную операцию чтения.
type: docs
weight: 248
url: /ru/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию чтения.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который будут записаны прочитанные байты. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов для чтения. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван после завершения операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции чтения. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию чтения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [Object](../../../system/object/)
* Класс [NetworkStream](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)