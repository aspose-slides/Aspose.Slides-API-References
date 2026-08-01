---
title: SelectSingleNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Selecteert een enkel knooppunt in de XPathNavigator met de opgegeven XPath-query.
type: docs
weight: 781
url: /nl/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) methode

Selecteert een enkel knooppunt in de [XPathNavigator](../) met de opgegeven [XPath](../../) query.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Een [String](../../../system/string/) die een [XPath](../../) expressie vertegenwoordigt. |

### Retourwaarde

Een [XPathNavigator](../) object dat het eerste overeenkomende knooppunt bevat voor de opgegeven [XPath](../../) query; anders **nullptr** als er geen queryresultaten zijn.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) methode

Selecteert een enkel knooppunt in het [XPathNavigator](../) object met de opgegeven [XPath](../../) query en het opgegeven [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object om namespace-prefixen op te lossen.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Een [String](../../../system/string/) die een [XPath](../../) expressie vertegenwoordigt. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat wordt gebruikt om namespace-prefixen in de [XPath](../../) query op te lossen. |

### Retourwaarde

Een [XPathNavigator](../) object dat het eerste overeenkomende knooppunt bevat voor de opgegeven [XPath](../../) query; anders **nullptr** als er geen queryresultaten zijn.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) methode

Selecteert een enkel knooppunt in de [XPathNavigator](../) met het opgegeven [XPathExpression](../../xpathexpression/) object.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Een [XPathExpression](../../xpathexpression/) object dat de gecompileerde [XPath](../../) query bevat. |

### Retourwaarde

Een [XPathNavigator](../) object dat het eerste overeenkomende knooppunt bevat voor de opgegeven [XPath](../../) query; anders **nullptr** als er geen queryresultaten zijn.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)