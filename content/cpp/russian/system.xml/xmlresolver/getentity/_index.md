---
title: GetEntity()
second_title: Aspose.Slides для справочника API C++
description: При переопределении в производном классе сопоставляет URI с объектом, содержащим фактический ресурс.
type: docs
weight: 14
url: /ru/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

При переопределении в производном классе сопоставляет URI с объектом, содержащим фактический ресурс.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, возвращённый вызовом [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | В настоящее время не используется. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Тип возвращаемого объекта. В текущей версии возвращаются только объекты Stream. |

### Возвращаемое значение

Объект потока или **nullptr**, если указан тип, отличный от потока.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [XmlResolver](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)