---
title: BeginGetHostEntry()
second_title: Справочник API Aspose.Slides для C++
description: Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-class, используя указанную строку, содержащую имя хоста или IP-адрес.
type: docs
weight: 105
url: /ru/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию по созданию нового экземпляра класса IPHostEntry, используя указанный строковый параметр, содержащий имя хоста или IP-адрес.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Строка, содержащая имя хоста или IP-адрес. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет выполнен после завершения операции. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) метод

Инициирует асинхронную операцию по созданию нового экземпляра класса IPHostEntry, используя указанный IP-адрес.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP-адрес. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Обратный вызов, который будет выполнен после завершения операции. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции. |

### Возвращаемое значение

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Типовое определение [AsyncCallback](../../../system/asynccallback/)
* Класс [IAsyncResult](../../../system/iasyncresult/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [Dns](../)
* Класс [IPAddress](../../ipaddress/)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)