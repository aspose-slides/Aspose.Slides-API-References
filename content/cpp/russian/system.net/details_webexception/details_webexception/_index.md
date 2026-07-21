---
title: Details_WebException()
second_title: Справка по API Aspose.Slides для C++
description: Создаёт новый экземпляр.
type: docs
weight: 40
url: /ru/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | [String](../../../system/string/) | Описание ошибки. |

## Details_WebException::Details_WebException(String, Exception) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | [String](../../../system/string/) | Сообщение исключения. |
| innerException | [Exception](../../../system/exception/) | Внутреннее исключение. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | [String](../../../system/string/) | Сообщение исключения. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Код состояния. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | [String](../../../system/string/) | Сообщение исключения. |
| innerException | [Exception](../../../system/exception/) | Внутреннее исключение. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Код состояния. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | Веб-ответ, с которым связано текущее исключение. |

## См. также

* Перечисление [WebExceptionStatus](../../webexceptionstatus/)
* Типовое определение [Exception](../../../system/exception/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Details_WebException](../)
* Класс [String](../../../system/string/)
* Класс [WebResponse](../../webresponse/)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)