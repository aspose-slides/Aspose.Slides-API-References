---
title: ChangeType()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанное значение, тип которого является одной из допустимых репрезентаций типа XML-схемы, представленного XmlSchemaDatatype, в указанный тип во время выполнения.
type: docs
weight: 66
url: /ru/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) метод


Преобразует указанное значение, тип которого является одной из допустимых репрезентаций типа XML-схемы, представленного [XmlSchemaDatatype](../), в указанный тип во время выполнения.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Входное значение для преобразования в указанный тип. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Целевой тип, в который нужно преобразовать входное значение. |

### Возвращаемое значение

Преобразованное входное значение.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) метод


Преобразует указанное значение, тип которого является одной из допустимых репрезентаций типа XML-схемы, представленного [XmlSchemaDatatype](../), в указанный тип во время выполнения с использованием [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), если [XmlSchemaDatatype](../) представляет тип **xs:QName** или тип, производный от него.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Входное значение для преобразования в указанный тип. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Целевой тип, в который нужно преобразовать входное значение. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён. Это имеет смысл только если [XmlSchemaDatatype](../) представляет тип **xs:QName** или тип, производный от него. |

### Возвращаемое значение

Преобразованное входное значение.

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [XmlSchemaDatatype](../)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Пространство имен [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)