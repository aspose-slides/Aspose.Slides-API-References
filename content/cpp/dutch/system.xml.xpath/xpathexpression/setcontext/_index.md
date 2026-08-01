---
title: SetContext()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, specificeert het XmlNamespaceManager-object dat gebruikt moet worden voor naamruimteoplossing.
type: docs
weight: 53
url: /nl/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) methode

Wanneer overschreven in een afgeleide klasse, specificeert het [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) object dat gebruikt wordt voor naamruimteoplossing.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Een [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) object dat gebruikt wordt voor naamruimteoplossing. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) methode

Wanneer overschreven in een afgeleide klasse, specificeert het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat gebruikt wordt voor naamruimteoplossing.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Een object dat de [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) interface implementeert en gebruikt wordt voor naamruimteoplossing. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Klasse [XPathExpression](../)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Naamruimte [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)