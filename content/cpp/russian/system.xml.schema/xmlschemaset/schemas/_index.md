---
title: Schemas()
second_title: Aspose.Slides для C++ справка API
description: Возвращает коллекцию всех схем языка определения XML Schema (XSD) в XmlSchemaSet.
type: docs
weight: 248
url: /ru/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() метод


Возвращает коллекцию всех схем языка описания XML [Schema](../../) (XSD) в [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### Возвращаемое значение

Объект IList, содержащий все схемы, которые были добавлены в [XmlSchemaSet](../). Если в [XmlSchemaSet](../) не было добавлено схем, возвращается пустая коллекция.

## XmlSchemaSet::Schemas(String) метод


Возвращает коллекцию всех схем языка описания XML [Schema](../../) (XSD) в [XmlSchemaSet](../), принадлежащих заданному пространству имён.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Свойство **targetNamespace** схемы. |

### Возвращаемое значение

Объект IList, содержащий все схемы, которые были добавлены в [XmlSchemaSet](../) и принадлежат заданному пространству имён. Если в [XmlSchemaSet](../) не было добавлено схем, возвращается пустая коллекция.

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IList](../../../system.collections.generic/ilist/)
* Класс [XmlSchema](../../xmlschema/)
* Класс [XmlSchemaSet](../)
* Класс [List](../../../system.collections.generic/list/)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)