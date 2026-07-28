---
title: SetContext()
second_title: Aspose.Slides C++ API referencia
description: Ha egy származtatott osztályban felülírják, meghatározza azt az XmlNamespaceManager objektumot, amelyet a névtér feloldásához használnak.
type: docs
weight: 53
url: /hu/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) metódus


Ha egy származtatott osztályban felülírják, meghatározza a [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) objektumot a névtér feloldásához használandó.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Egy [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) objektum a névtér feloldásához használandó. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) metódus


Ha egy származtatott osztályban felülírják, meghatározza a [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektumot a névtér feloldásához használandó.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Egy objektum, amely implementálja a [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) interfészt a névtér feloldásához használandó. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Osztály [XPathExpression](../)
* Osztály [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)