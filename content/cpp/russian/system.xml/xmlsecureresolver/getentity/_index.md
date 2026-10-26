---
title: GetEntity()
second_title: Справочник API Aspose.Slides для C++
description: Отображает URI в объект, содержащий реальный ресурс.
type: docs
weight: 27
url: /ru/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) метод

Отображает URI в объект, содержащий реальный ресурс.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, который возвращается вызовом [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | В настоящий момент не используется. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Тип возвращаемого объекта. В текущей версии возвращаются только объекты Stream. |

### Возвращаемое значение

Поток, возвращаемый вызовом **GetEntity** у базового [XmlResolver](../../xmlresolver/). Если указан тип, отличный от Stream, метод возвращает **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [XmlSecureResolver](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)