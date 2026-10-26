---
title: Uri()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт объект Uri, представляющий указанный URI.
type: docs
weight: 287
url: /ru/system/uri/uri/
---
## Uri::Uri(const String\&) constructor


Создаёт объект [Uri](../), представляющий указанный URI.

```cpp
System::Uri::Uri(const String &uriString)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |

## Uri::Uri(const String\&, bool) constructor


Создаёт объект [Uri](../), представляющий указанный URI; параметр указывает, следует ли экранировать URI.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| dontEscape | **bool** | Specifies if the URI should not be escaped |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) constructor


Создаёт объект [Uri](../) из указанного объекта [Uri](../), представляющего базовый URI, и строкового представления относительного URI; параметр указывает, следует ли экранировать URI.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [String](../../string/)\& | The relative URI that is added to the base URI |
| dontEscape | **bool** | Specifies if the URI should not be escaped |

## Uri::Uri(const String\&, UriKind) constructor


Создаёт объект [Uri](../), представляющий указанный URI; параметр указывает тип URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| uriKind | [UriKind](../../urikind/) | Specifies the URI kind |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) constructor


Создаёт объект [Uri](../) из указанных базового и относительного URI.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [String](../../string/)\& | The relative URI that is added to the base URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) constructor


Создаёт объект [Uri](../) из указанных базового и относительного URI.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The relative URI that is added to the base URI |

## See Also

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Uri](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)