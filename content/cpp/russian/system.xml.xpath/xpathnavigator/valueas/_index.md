---
title: ValueAs()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает значение текущего узла как указанный Type, используя указанный объект IXmlNamespaceResolver для разрешения префиксов пространств имён.
type: docs
weight: 378
url: /ru/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) метод

Возвращает значение текущего узла как указанный Type, используя объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения префиксов пространств имён.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Type, которым возвращается значение текущего узла. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён. |

### Возвращаемое значение

Значение текущего узла как запрошенный Type.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)