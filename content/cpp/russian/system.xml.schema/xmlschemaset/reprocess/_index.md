---
title: Reprocess()
second_title: Aspose.Slides для C++ API Reference
description: Повторно обрабатывает XML Schema definition language (XSD) схему, уже существующую в XmlSchemaSet.
type: docs
weight: 222
url: /ru/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) метод

Повторно обрабатывает схему XML [Schema](../../) definition language (XSD), уже существующую в [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Схема для повторной обработки. |

### Возвращаемое значение

Объект [XmlSchema](../../xmlschema/), если схема является корректной. Если схема недействительна и указан ValidationEventHandler, возвращается **nullptr**, и генерируется соответствующее событие проверки. В противном случае выбрасывается XmlSchemaException.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchema](../../xmlschema/)
* Класс [XmlSchemaSet](../)
* Пространство имен [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)