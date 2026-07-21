---
title: BeginResolve()
second_title: Aspose.Slides для C++ справочник API
description: Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-class с использованием указанного имени хоста.
type: docs
weight: 157
url: /ru/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-class с использованием указанного имени хоста.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Имя хоста, используемое для создания нового экземпляра класса [IPHostEntry](../../iphostentry/). |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет выполнен после завершения операции. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Данные, предоставленные пользователем, используемые для уникальной идентификации каждой асинхронной операции. |

### Return Value

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [Dns](../)
* Пространство имен [System::Net](../../)
* Library [Aspose.Slides](../../../)