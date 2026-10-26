---
title: BeginGetHostByName()
second_title: Aspose.Slides для C++ справочник API
description: Инициирует асинхронную операцию по созданию нового экземпляра класса IPHostEntry с использованием указанного имени хоста.
type: docs
weight: 53
url: /ru/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) метод


Инициирует асинхронную операцию по созданию нового экземпляра класса IPHostEntry с использованием указанного имени хоста.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Имя хоста. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван при завершении операции. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [Dns](../)
* Пространство имён [System::Net](../../)
* Library [Aspose.Slides](../../../)