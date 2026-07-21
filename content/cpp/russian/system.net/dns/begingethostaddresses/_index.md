---
title: BeginGetHostAddresses()
second_title: Справочник API Aspose.Slides для C++
description: Инициирует асинхронную операцию по созданию нового экземпляра класса IPHostEntry-class, используя указанную строку, содержащую имя хоста или IP-адрес.
type: docs
weight: 131
url: /ru/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) метод

Запускает асинхронную операцию по созданию нового экземпляра класса IPHostEntry, используя указанную строку, содержащую имя хоста или IP-адрес.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Строка, содержащая имя хоста или IP-адрес. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет вызван по завершении операции. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Данные, предоставленные пользователем, используемые для уникальной идентификации каждой асинхронной операции. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [Dns](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)