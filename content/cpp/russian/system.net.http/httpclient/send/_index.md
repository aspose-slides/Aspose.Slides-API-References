---
title: Send()
second_title: Aspose.Slides для C++ справочник API
description: Отправляет указанный HTTP-запрос.
type: docs
weight: 118
url: /ru/system.net.http/httpclient/send/
---
## HttpClient::Send(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) метод


Отправляет указанный HTTP-запрос.

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClient::Send(System::SharedPtr<HttpRequestMessage> request, HttpCompletionOption completionOption)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | HTTP-запрос, который необходимо отправить. |
| completionOption | [HttpCompletionOption](../../httpcompletionoption/) | Значение, указывающее, когда завершать операцию. |

## См. также

* Перечисление [HttpCompletionOption](../../httpcompletionoption/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [HttpResponseMessage](../../httpresponsemessage/)
* Класс [HttpRequestMessage](../../httprequestmessage/)
* Класс [HttpClient](../)
* Пространство имён [System::Net::Http](../../)
* Библиотека [Aspose.Slides](../../../)