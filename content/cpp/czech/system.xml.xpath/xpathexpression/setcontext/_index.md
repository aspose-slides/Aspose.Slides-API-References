---
title: SetContext()
second_title: Aspose.Slides pro C++ API Reference
description: Při přepsání v odvozené třídě určuje objekt XmlNamespaceManager, který se použije pro rozlišení jmenných prostorů.
type: docs
weight: 53
url: /cs/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) metoda

Při přepsání v odvozené třídě určuje objekt [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) použitý pro rozlišení jmenných prostorů.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Objekt [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) použitý pro rozlišení jmenných prostorů. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) metoda

Při přepsání v odvozené třídě určuje objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) použitý pro rozlišení jmenných prostorů.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objekt, který implementuje rozhraní [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) a je použit pro rozlišení jmenných prostorů. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Třída [XPathExpression](../)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)