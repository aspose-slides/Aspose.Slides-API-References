---
title: Add()
second_title: Aspose.Slides для C++: справочник API
description: Добавляет схему языка определения XML Schema (XSD) по указанному URL в XmlSchemaSet.
type: docs
weight: 157
url: /ru/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) метод


Добавляет схему языка определения XML [Schema](../../) (XSD) по указанному URL в [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Значение **targetNamespace** схемы или **nullptr**, чтобы использовать **targetNamespace**, указанный в схеме. |
| schemaUri | const [String](../../../system/string/)\& | URL, указывающий схему для загрузки. |

### Возвращаемое значение

Возвращает объект [XmlSchema](../../xmlschema/), если схема действительна. Если схема недействительна и указан ValidationEventHandler, то возвращается **nullptr**, и генерируется соответствующее событие проверки. В противном случае выбрасывается XmlSchemaException.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) метод


Добавляет схему языка определения XML [Schema](../../) (XSD), содержащуюся в [XmlReader](../../../system.xml/xmlreader/), в [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Значение **targetNamespace** схемы или **nullptr**, чтобы использовать **targetNamespace**, указанный в схеме. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/). |

### Возвращаемое значение

Возвращает объект [XmlSchema](../../xmlschema/), если схема действительна. Если схема недействительна и указан ValidationEventHandler, то возвращается **nullptr**, и генерируется соответствующее событие проверки. В противном случае выбрасывается XmlSchemaException.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) метод


Добавляет все схемы языка определения XML [Schema](../../) (XSD), находящиеся в указанном [XmlSchemaSet](../), в [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | Объект [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) метод


Добавляет указанный [XmlSchema](../../xmlschema/) в [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Объект [XmlSchema](../../xmlschema/) для добавления в [XmlSchemaSet](../). |

### Возвращаемое значение

Возвращает объект [XmlSchema](../../xmlschema/), если схема действительна. Если схема недействительна и указан ValidationEventHandler, то возвращается **nullptr**, и генерируется соответствующее событие проверки. В противном случае выбрасывается XmlSchemaException.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchema](../../xmlschema/)
* Класс [String](../../../system/string/)
* Класс [XmlSchemaSet](../)
* Класс [XmlReader](../../../system.xml/xmlreader/)
* Пространство имен [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)