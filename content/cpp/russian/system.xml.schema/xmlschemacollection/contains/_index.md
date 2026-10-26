---
title: Contains()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает значение, указывающее, находится ли targetNamespace указанного XmlSchema в коллекции.
type: docs
weight: 66
url: /ru/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) метод

Возвращает значение, указывающее, находится ли **targetNamespace** указанного [XmlSchema](../../xmlschema/) в коллекции.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Объект [XmlSchema](../../xmlschema/). |

### Возвращаемое значение

**true**, если в коллекции есть схема с тем же **targetNamespace**; в противном случае **false**.

## XmlSchemaCollection::Contains(const String\&) метод

Возвращает значение, указывающее, находится ли схема с указанным пространством имён в коллекции.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI пространства имён, связанный со схемой. Для XML-схем обычно используется целевое пространство имён. |

### Возвращаемое значение

**true**, если в коллекции есть схема с указанным пространством имён; в противном случае **false**.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchema](../../xmlschema/)
* Класс [XmlSchemaCollection](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)