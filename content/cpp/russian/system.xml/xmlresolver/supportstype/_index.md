---
title: SupportsType()
second_title: Aspose.Slides для C++ — справка по API
description: Позволяет резолверу возвращать типы, отличные от Stream.
type: docs
weight: 40
url: /ru/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) метод


Позволяет резолверу возвращать типы, отличные от Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Тип для возврата. |

### Возвращаемое значение

**true** если **type** поддерживается; в противном случае, **false**.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Uri](../../../system/uri/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [XmlResolver](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)