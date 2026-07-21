---
title: CreateHttp()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый экземпляр класса WebRequest, используя указанный URI.
type: docs
weight: 79
url: /ru/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) метод

Создает новый экземпляр класса [WebRequest](../) с использованием указанного URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | URI, который используется для создания нового экземпляра класса [WebRequest](../). |

### Возвращаемое значение

Новосозданный экземпляр класса WebRequest.

## Примечания

Исключение NotSupportedException будет выброшено, когда указанный URI начинается с любой схемы, кроме [http://](http://) или [https://](https://).

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) метод

Создает новый экземпляр класса [WebRequest](../) с использованием указанного URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, который используется для создания нового экземпляра класса [WebRequest](../). |

### Возвращаемое значение

Новосозданный экземпляр класса WebRequest.

## Примечания

Исключение NotSupportedException будет выброшено, когда указанный URI начинается с любой схемы, кроме [http://](http://) или [https://](https://).

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [HttpWebRequest](../../httpwebrequest/)
* Класс [String](../../../system/string/)
* Класс [WebRequest](../)
* Класс [Uri](../../../system/uri/)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)