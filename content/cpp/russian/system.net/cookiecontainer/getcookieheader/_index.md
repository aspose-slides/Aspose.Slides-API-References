---
title: GetCookieHeader()
second_title: Aspose.Slides для C++ справка API
description: Возвращает HTTP-заголовок, содержащий куки, связанные с указанным URI.
type: docs
weight: 170
url: /ru/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) метод


Возвращает HTTP-заголовок, содержащий куки, связанные с указанным URI.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, для которого будет построено имя заголовка. |

### Возвращаемое значение

HTTP-заголовок, содержащий куки, связанные с указанным URI.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) метод


Возвращает HTTP-заголовок, содержащий куки, связанные с указанным URI.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, для которого будет построено имя заголовка. |
| optCookie2 | [String](../../../system/string/)\& | Выходной параметр, в который будет записана кука с максимальной поддерживаемой версией. |

### Возвращаемое значение

HTTP-заголовок, содержащий куки, связанные с указанным URI.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Uri](../../../system/uri/)
* Класс [CookieContainer](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)