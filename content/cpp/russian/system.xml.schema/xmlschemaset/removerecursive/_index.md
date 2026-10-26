---
title: RemoveRecursive()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет указанную схему определения XML Schema (XSD) и все схемы, импортируемые ею, из XmlSchemaSet.
type: docs
weight: 183
url: /ru/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) метод


Удаляет указанную XML [Schema](../../) definition language (XSD) схему и все схемы, импортируемые ею, из [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) объект, который следует удалить из [XmlSchemaSet](../). |

### Возвращаемое значение

**true** если объект [XmlSchema](../../xmlschema/) и все его импорты были успешно удалены; иначе, **false**.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchema](../../xmlschema/)
* Класс [XmlSchemaSet](../)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)