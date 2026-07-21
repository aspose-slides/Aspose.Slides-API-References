---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает XmlSchemaSimpleType, который представляет встроенный простой тип простого типа, указанный квалифицированным именем.
type: docs
weight: 183
url: /ru/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) метод

Возвращает [XmlSchemaSimpleType](../../xmlschemasimpletype/), который представляет встроенный простой тип простого типа, указанный квалифицированным именем.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | Значение [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) простого типа. |

### Возвращаемое значение

Объект [XmlSchemaSimpleType](../../xmlschemasimpletype/), представляющий встроенный простой тип.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) метод

Возвращает [XmlSchemaSimpleType](../../xmlschemasimpletype/), который представляет встроенный простой тип указанного простого типа.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Одно из значений XmlTypeCode, представляющих простой тип. |

### Возвращаемое значение

Объект [XmlSchemaSimpleType](../../xmlschemasimpletype/), представляющий встроенный простой тип.

## См. также

* Перечисление [XmlTypeCode](../../xmltypecode/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Класс [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Класс [XmlSchemaType](../)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)