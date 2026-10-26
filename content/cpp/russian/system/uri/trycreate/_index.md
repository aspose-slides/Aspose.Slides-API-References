---
title: TryCreate()
second_title: Справка API Aspose.Slides для C++
description: Создаёт объект Uri, представляющий указанный URI; аргумент указывает тип URI.
type: docs
weight: 508
url: /ru/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) метод


Создает объект [Uri](../), представляющий указанный URI; аргумент указывает тип URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Строка URI, которую будет представлять создаваемый объект |
| uriKind | [UriKind](../../urikind/) | Указывает тип URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Выходной аргумент, который при успешном создании указывает на вновь созданный объект [Uri](../) при возврате из метода |

### Возвращаемое значение

True, если создание удалось, иначе — false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) метод


Создает объект [Uri](../) из указанного объекта [Uri](../), представляющего базовый URI, и строкового представления относительного URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Базовый URI |
| relativeUri | const [String](../../string/)\& | Относительный URI, добавляемый к базовому URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Выходной аргумент, который при успешном создании указывает на вновь созданный объект [Uri](../) при возврате из метода |

### Возвращаемое значение

True, если создание удалось, иначе — false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) метод


Создает объект [Uri](../) из указанных базового и относительного URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Базовый URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Относительный URI, добавляемый к базовому URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Выходной аргумент, который при успешном создании указывает на вновь созданный объект [Uri](../) при возврате из метода |

### Возвращаемое значение

True, если создание удалось, иначе — false

## См. также

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Uri](../)
* Пространство имен [System](../../)
* Library [Aspose.Slides](../../../)