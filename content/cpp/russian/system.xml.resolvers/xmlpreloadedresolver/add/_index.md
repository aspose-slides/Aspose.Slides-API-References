---
title: Add()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет массив байтов в хранилище XmlPreloadedResolver и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется.
type: docs
weight: 79
url: /ru/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) метод


Добавляет массив байтов в хранилище [XmlPreloadedResolver](../) и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI данных, которые добавляются в хранилище [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов с данными, соответствующими указанному URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод


Добавляет массив байтов в хранилище [XmlPreloadedResolver](../) и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI данных, которые добавляются в хранилище [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов с данными, соответствующими указанному URI. |
| offset | **int32_t** | Смещение в переданном массиве байтов, с которого начинаются данные. |
| count | **int32_t** | Количество байтов для чтения из массива, начиная с указанного смещения. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) метод


Добавляет объект Stream в хранилище [XmlPreloadedResolver](../) и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI данных, которые добавляются в хранилище [XmlPreloadedResolver](../). |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Объект Stream с данными, соответствующими указанному URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) метод


Добавляет строку с предзагруженными данными в хранилище [XmlPreloadedResolver](../) и сопоставляет её с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI данных, которые добавляются в хранилище [XmlPreloadedResolver](../). |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) с данными, соответствующими указанному URI. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)