---
title: SetContext()
second_title: Aspose.Slides для C++: справочник API
description: Когда переопределяется в производном классе, указывает объект XmlNamespaceManager, используемый для разрешения пространств имён.
type: docs
weight: 53
url: /ru/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) метод

Когда переопределяется в производном классе, указывает объект [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) для разрешения пространств имён.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Объект [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/), используемый для разрешения пространств имён. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) метод

Когда переопределяется в производном классе, указывает объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения пространств имён.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Объект, реализующий интерфейс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения пространств имён. |

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Класс [XPathExpression](../)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)