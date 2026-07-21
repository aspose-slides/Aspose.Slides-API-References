---
title: get_SchemaInfo()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает информацию схемы, назначенную текущему узлу в результате проверки схемы.
type: docs
weight: 196
url: /ru/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() метод

Возвращает информацию схемы, назначенную текущему узлу в результате проверки схемы.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### Возвращаемое значение

Объект IXmlSchemaInfo, содержащий информацию схемы для текущего узла. [Schema](../../../system.xml.schema/) информация может быть установлена для элементов, атрибутов или текстовых узлов с ненулевым значением [XmlReader::get_ValueType](../get_valuetype/). Если текущий узел не является одним из перечисленных типов узлов, или если экземпляр [XmlReader](../) не сообщает информацию схемы, этот метод возвращает **nullptr**. Если этот метод вызывается из объекта [XmlTextReader](../../xmltextreader/) или [XmlValidatingReader](../../xmlvalidatingreader/), он всегда возвращает **nullptr**. Эти реализации [XmlReader](../) не раскрывают информацию схемы через метод get_SchemaInfo.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)