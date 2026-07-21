---
title: GetBuiltInComplexType()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает объект XmlSchemaComplexType, представляющий встроенный сложный тип указанного сложного типа.
type: docs
weight: 196
url: /ru/system.xml.schema/xmlschematype/getbuiltincomplextype/
---
## XmlSchemaType::GetBuiltInComplexType(XmlTypeCode) метод

Возвращает [XmlSchemaComplexType](../../xmlschemacomplextype/), представляющий встроенный сложный тип указанного сложного типа.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(XmlTypeCode typeCode)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Одно из значений XmlTypeCode, представляющих сложный тип. |

### Возвращаемое значение

[XmlSchemaComplexType](../../xmlschemacomplextype/), представляющий встроенный сложный тип.

## XmlSchemaType::GetBuiltInComplexType(const SharedPtr\<XmlQualifiedName\>\&) метод

Возвращает [XmlSchemaComplexType](../../xmlschemacomplextype/), представляющий встроенный сложный тип, указанный квалифицированным именем.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) сложного типа. |

### Возвращаемое значение

[XmlSchemaComplexType](../../xmlschemacomplextype/), представляющий встроенный сложный тип.

## См. также

* Перечисление [XmlTypeCode](../../xmltypecode/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchemaComplexType](../../xmlschemacomplextype/)
* Класс [XmlSchemaType](../)
* Класс [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)