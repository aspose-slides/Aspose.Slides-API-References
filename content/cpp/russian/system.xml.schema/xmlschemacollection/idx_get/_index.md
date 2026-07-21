---
title: idx_get()
second_title: Aspose.Slides для C++: справочник API
description: Возвращает XmlSchema, связанный с указанным URI пространства имен.
type: docs
weight: 53
url: /ru/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) метод


Возвращает [XmlSchema](../../xmlschema/), связанный с указанным URI пространства имен.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI пространства имен, связанный со схемой, которую вы хотите вернуть. Обычно это **targetNamespace** схемы. |

### Возвращаемое значение

[XmlSchema](../../xmlschema/), связанный с URI пространства имен; **nullptr**, если нет загруженной схемы, связанной с указанным пространством имен, или если пространство имен связано со схемой XDR.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchema](../../xmlschema/)
* Класс [String](../../../system/string/)
* Класс [XmlSchemaCollection](../)
* Пространство имен [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)