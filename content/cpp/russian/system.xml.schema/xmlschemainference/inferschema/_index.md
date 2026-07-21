---
title: InferSchema()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт схему XML Schema Definition Language (XSD) на основе XML-документа, содержащегося в указанном объекте XmlReader.
type: docs
weight: 66
url: /ru/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) метод

Выводит схему XML [Schema](../../) Definition Language (XSD) из XML-документа, содержащегося в указанном объекте [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий XML-документ, из которого выводится схема. |

### Возвращаемое значение

Объект [XmlSchemaSet](../../xmlschemaset/), содержащий полученные схемы.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) метод

Выводит схему XML [Schema](../../) Definition Language (XSD) из XML-документа, содержащегося в указанном объекте [XmlReader](../../../system.xml/xmlreader/), и уточняет полученную схему, используя существующую схему из указанного объекта [XmlSchemaSet](../../xmlschemaset/) с тем же целевым пространством имён.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий XML-документ, из которого выводится схема. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Объект [XmlSchemaSet](../../xmlschemaset/), содержащий существующую схему, используемую для уточнения полученной схемы. |

### Возвращаемое значение

Объект [XmlSchemaSet](../../xmlschemaset/), содержащий полученные схемы.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* класс [XmlSchemaSet](../../xmlschemaset/)
* класс [XmlReader](../../../system.xml/xmlreader/)
* класс [XmlSchemaInference](../)
* пространство имён [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)