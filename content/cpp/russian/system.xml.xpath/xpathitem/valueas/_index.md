---
title: ValueAs()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает значение элемента как указанный тип.
type: docs
weight: 131
url: /ru/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) метод

Возвращает значение элемента как указанный тип.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Тип, в который возвращается значение элемента. |

### Возвращаемое значение

Значение элемента в запрошенном типе.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) метод

При переопределении в производном классе возвращает значение элемента в типе, указанном с помощью объекта [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемого для разрешения префиксов пространств имён.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Тип, в который возвращается значение элемента. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён. |

### Возвращаемое значение

Значение элемента в запрошенном типе.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [XPathItem](../)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)