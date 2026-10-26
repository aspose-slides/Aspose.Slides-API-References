---
title: Remove()
second_title: Справочник API Aspose.Slides for C++
description: Удаляет указанную схему языка определения XML Schema (XSD) из XmlSchemaSet.
type: docs
weight: 170
url: /ru/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) метод

Удаляет указанную схему языка определения XML [Schema](../../) (XSD) из [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Объект [XmlSchema](../../xmlschema/), который нужно удалить из [XmlSchemaSet](../). |

### Возвращаемое значение

Объект [XmlSchema](../../xmlschema/), удалённый из [XmlSchemaSet](../), или **nullptr**, если схема не найдена в [XmlSchemaSet](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchema](../../xmlschema/)
* Класс [XmlSchemaSet](../)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)