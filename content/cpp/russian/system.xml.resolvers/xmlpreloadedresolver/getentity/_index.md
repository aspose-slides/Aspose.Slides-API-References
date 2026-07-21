---
title: GetEntity()
second_title: Справочник API Aspose.Slides для C++
description: Отображает URI на объект, содержащий фактический ресурс.
type: docs
weight: 53
url: /ru/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method


Отображает URI на объект, содержащий фактический ресурс.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, возвращаемый вызовом [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | В настоящее время не используется. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Тип объекта, который необходимо вернуть. [XmlPreloadedResolver](../) поддерживает объекты Stream и TextReader для URI, которые были добавлены как [String](../../../system/string/). Если запрошенный тип не поддерживается разрешителем, будет выброшено исключение. Используйте метод XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) для определения, поддерживается ли определённый **Type** этим разрешителем. |

### Возвращаемое значение

Объект Stream или TextReader, соответствующий фактическому источнику.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [XmlPreloadedResolver](../)
* Пространство имён [System::Xml::Resolvers](../../)
* Библиотека [Aspose.Slides](../../../)