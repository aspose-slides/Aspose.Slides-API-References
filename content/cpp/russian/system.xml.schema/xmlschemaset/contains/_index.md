---
title: Contains()
second_title: Aspose.Slides для C++ справочник API
description: Указывает, находится ли схема языка определения XML Schema (XSD) с указанным URI целевого пространства имён в XmlSchemaSet.
type: docs
weight: 196
url: /ru/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) метод

Указывает, находится ли схема XML [Schema](../../) definition language (XSD) с указанным URI целевого пространства имён в [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Свойство **targetNamespace** схемы. |

### Возвращаемое значение

**true** если схема с указанным URI целевого пространства имён находится в [XmlSchemaSet](../); иначе **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) метод

Указывает, находится ли указанный объект XML [Schema](../../) definition language (XSD) [XmlSchema](../../xmlschema/) в [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Объект [XmlSchema](../../xmlschema/). |

### Возвращаемое значение

**true** если объект [XmlSchema](../../xmlschema/) находится в [XmlSchemaSet](../); иначе **false**.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlSchema](../../xmlschema/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)