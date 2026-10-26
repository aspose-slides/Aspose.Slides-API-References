---
title: ReadElementContentAs()
second_title: Aspose.Slides для C++ справочник API
description: Читает содержимое элемента как запрашиваемый тип.
type: docs
weight: 586
url: /ru/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) метод

Читает содержимое элемента как запрашиваемый тип.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Тип возвращаемого значения. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), используемый для разрешения любых префиксов пространств имён, связанных с преобразованием типов. |

### Возвращаемое значение

Содержимое элемента, преобразованное в запрашиваемый типизированный объект.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) метод

Проверяет, что указанное локальное имя и URI пространства имён совпадают с текущим элементом, затем читает содержимое элемента как запрашиваемый тип.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Тип возвращаемого значения. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), используемый для разрешения любых префиксов пространств имён, связанных с преобразованием типов. |
| localName | [String](../../../system/string/) | Локальное имя элемента. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён элемента. |

### Возвращаемое значение

Содержимое элемента, преобразованное в запрашиваемый типизированный объект.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Класс [XmlReader](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)