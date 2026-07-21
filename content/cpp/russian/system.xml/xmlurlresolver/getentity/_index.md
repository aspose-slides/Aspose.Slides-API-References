---
title: GetEntity()
second_title: Справочник API Aspose.Slides для C++
description: Отображает URI в объект, содержащий фактический ресурс.
type: docs
weight: 53
url: /ru/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) метод

Отображает URI в объект, содержащий фактический ресурс.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, возвращённый вызовом [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | В настоящее время не используется. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Тип возвращаемого объекта. Текущая реализация возвращает только объекты Stream. |

### Возвращаемое значение

Объект stream или **nullptr**, если указан тип, отличный от stream.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [XmlUrlResolver](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)