---
title: SetContext()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, gibt das XmlNamespaceManager-Objekt an, das für die Namensauflösung verwendet werden soll.
type: docs
weight: 53
url: /de/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) Methode


Wenn in einer abgeleiteten Klasse überschrieben, gibt das [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)-Objekt an, das für die Namensauflösung verwendet werden soll.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Ein [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)-Objekt, das für die Namensauflösung verwendet wird. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) Methode


Wenn in einer abgeleiteten Klasse überschrieben, gibt das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt an, das für die Namensauflösung verwendet werden soll.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Ein Objekt, das das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Interface implementiert und für die Namensauflösung verwendet wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Klasse [XPathExpression](../)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namensraum [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)