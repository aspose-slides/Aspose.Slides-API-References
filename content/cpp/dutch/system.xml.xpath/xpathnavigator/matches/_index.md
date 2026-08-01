---
title: Matches()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of het huidige knooppunt overeenkomt met de gespecificeerde XPathExpression.
type: docs
weight: 820
url: /nl/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) methode


Bepaalt of het huidige knooppunt overeenkomt met de opgegeven [XPathExpression](../../xpathexpression/).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Een [XPathExpression](../../xpathexpression/) object dat de gecompileerde [XPath](../../) expressie bevat. |

### Retourwaarde

**true** als het huidige knooppunt overeenkomt met de [XPathExpression](../../xpathexpression/); anders, **false**.

## XPathNavigator::Matches(String) methode


Bepaalt of het huidige knooppunt overeenkomt met de opgegeven [XPath](../../) expressie.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | De [XPath](../../) expressie. |

### Retourwaarde

**true** als het huidige knooppunt overeenkomt met de opgegeven [XPath](../../) expressie; anders, **false**.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathExpression](../../xpathexpression/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)