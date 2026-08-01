---
title: MoveToNext()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, verplaatst de XPathNavigator naar het volgende broederknooppunt van het huidige knooppunt.
type: docs
weight: 586
url: /nl/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() methode


Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](../) naar het volgende broederknooppunt van het huidige knooppunt.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### Retourwaarde

**true** als de [XPathNavigator](../) succesvol is verplaatst naar het volgende broederknooppunt; anders **false** als er geen verdere broeders meer zijn of als de [XPathNavigator](../) momenteel op een attribuutknooppunt staat. Als **false**, blijft de positie van de [XPathNavigator](../) onveranderd.

## XPathNavigator::MoveToNext(String, String) methode


Verplaatst de [XPathNavigator](../) naar het volgende broederknooppunt met de opgegeven lokale naam en namespace URI.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het volgende broederknooppunt waarnaar verplaatst moet worden. |
| namespaceURI | [String](../../../system/string/) | De namespace URI van het volgende broederknooppunt waarnaar verplaatst moet worden. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol is verplaatst naar het volgende broederknooppunt; **false** als er geen verdere broeders meer zijn, of als de [XPathNavigator](../) momenteel op een attribuutknooppunt staat. Als **false**, blijft de positie van de [XPathNavigator](../) onveranderd.

## XPathNavigator::MoveToNext(XPathNodeType) methode


Verplaatst de [XPathNavigator](../) naar het volgende broederknooppunt van het huidige knooppunt dat overeenkomt met het opgegeven XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Het XPathNodeType van het broederknooppunt waarnaar verplaatst moet worden. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol is verplaatst naar het volgende broederknooppunt; anders **false** als er geen verdere broeders meer zijn of als de [XPathNavigator](../) momenteel op een attribuutknooppunt staat. Als **false**, blijft de positie van de [XPathNavigator](../) onveranderd.

## Zie ook

* Enum [XPathNodeType](../../xpathnodetype/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)