---
title: ParseValue()
second_title: Aspose.Slides для C++ справка API
description: При переопределении в производном классе проверяет указанную строку на соответствие встроенному или пользовательскому простому типу.
type: docs
weight: 53
url: /ru/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) метод

При переопределении в производном классе проверяет указанный **string** на соответствие встроенному или пользовательскому простому типу.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | [String](../../../system/string/) | Введённый **string** для проверки против простого типа. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | [XmlNameTable](../../../system.xml/xmlnametable/) для атомизации при разборе **string**, если этот объект [XmlSchemaDatatype](../) представляет тип **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) объект, используемый при разборе **string**, если этот объект [XmlSchemaDatatype](../) представляет тип **xs:QName**. |

### Возвращаемое значение

Объект [Object](../../../system/object/), который можно безопасно привести к типу, возвращаемому вызовом [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [String](../../../system/string/)
* Класс [XmlNameTable](../../../system.xml/xmlnametable/)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Класс [XmlSchemaDatatype](../)
* Пространство имен [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)