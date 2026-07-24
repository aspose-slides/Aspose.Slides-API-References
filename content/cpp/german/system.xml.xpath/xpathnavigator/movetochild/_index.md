---
title: MoveToChild()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschiebt den XPathNavigator zum Kindknoten mit dem angegebenen lokalen Namen und Namespace-URI.
type: docs
weight: 690
url: /de/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) Methode

Verschiebt das [XPathNavigator](../) zum Kindknoten mit dem angegebenen lokalen Namen und dem angegebenen Namespace-URI.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Kindknotens, zu dem verschoben werden soll. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Kindknotens, zu dem verschoben werden soll. |

### Rückgabewert

**true** wenn das [XPathNavigator](../) erfolgreich zum Kindknoten verschoben wird; andernfalls **false**. Wenn **false**, bleibt die Position des [XPathNavigator](../) unverändert.

## XPathNavigator::MoveToChild(XPathNodeType) Methode

Verschiebt das [XPathNavigator](../) zum Kindknoten des angegebenen XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Der XPathNodeType des Kindknotens, zu dem verschoben werden soll. |

### Rückgabewert

**true** wenn das [XPathNavigator](../) erfolgreich zum Kindknoten verschoben wird; andernfalls **false**. Wenn **false**, bleibt die Position des [XPathNavigator](../) unverändert.

## Siehe auch

* Enum [XPathNodeType](../../xpathnodetype/)
* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)