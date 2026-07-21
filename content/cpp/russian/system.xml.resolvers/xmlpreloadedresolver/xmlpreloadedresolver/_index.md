---
title: XmlPreloadedResolver()
second_title: Aspose.Slides для C++ справочник API
description: Инициализирует новый экземпляр класса XmlPreloadedResolver.
type: docs
weight: 27
url: /ru/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() конструктор

Инициализирует новый экземпляр класса [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) конструктор

Инициализирует новый экземпляр класса [XmlPreloadedResolver](../) с указанными предварительно загруженными известными DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Известные DTD, которые должны быть предзаполнены в кэш. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) конструктор

Инициализирует новый экземпляр класса [XmlPreloadedResolver](../) с указанным резервным резольвером.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) или ваш собственный резольвер. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) конструктор

Инициализирует новый экземпляр класса [XmlPreloadedResolver](../) с указанным резервным резольвером и предварительно загруженными известными DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) или ваш собственный резольвер. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Известные DTD, которые должны быть предзаполнены в кэш. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) конструктор

Инициализирует новый экземпляр класса [XmlPreloadedResolver](../) с указанным резервным резольвером, предварительно загруженными известными DTD и сравнивателем равенства URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) или ваш собственный резольвер. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Известные DTD, которые должны быть предзаполнены в кэш. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | Реализация интерфейса IEqualityComparer, используемая при сравнении URI. |

## См. также

* Перечисление [XmlKnownDtds](../../xmlknowndtds/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlPreloadedResolver](../)
* Класс [XmlResolver](../../../system.xml/xmlresolver/)
* Класс [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Класс [Uri](../../../system/uri/)
* Пространство имён [System::Xml::Resolvers](../../)
* Библиотека [Aspose.Slides](../../../)