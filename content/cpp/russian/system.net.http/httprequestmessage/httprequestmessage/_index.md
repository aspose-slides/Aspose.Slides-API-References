---
title: HttpRequestMessage()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр.
type: docs
weight: 131
url: /ru/system.net.http/httprequestmessage/httprequestmessage/
---
## HttpRequestMessage::HttpRequestMessage() конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage()
```

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, System::SharedPtr<Uri> requestUri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | Метод HTTP. |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI запрашиваемого ресурса. |

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, String) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, String requestUri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | Метод HTTP. |
| requestUri | [String](../../../system/string/) | URI запрашиваемого ресурса. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [HttpRequestMessage](../)
* Класс [HttpMethod](../../httpmethod/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Пространство имён [System::Net::Http](../../)
* Библиотека [Aspose.Slides](../../../)