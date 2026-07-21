---
title: ReadContentAs()
second_title: Справочник API Aspose.Slides для C++
description: Считывает содержимое как объект указанного типа.
type: docs
weight: 456
url: /ru/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) метод


Считывает содержимое как объект указанного типа.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Тип возвращаемого значения. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), используемый для разрешения любых префиксов пространств имён, связанных с преобразованием типов. Например, его можно использовать при преобразовании объекта [XmlQualifiedName](../../xmlqualifiedname/) в **xs:string**. Это значение может быть **nullptr**. |

### Возвращаемое значение

Конкатенированное текстовое содержимое или значение атрибута, преобразованные в запрошенный тип.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)