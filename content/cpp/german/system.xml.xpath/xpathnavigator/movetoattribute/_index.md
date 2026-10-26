---
title: MoveToAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschiebt den XPathNavigator zum Attribut mit dem passenden lokalen Namen und Namespace-URI.
type: docs
weight: 495
url: /de/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute(String, String) Methode

Verschiebt den [XPathNavigator](../) zum Attribut mit dem passenden lokalen Namen und Namespace-URI.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs; **nullptr** für einen leeren Namespace. |

### Rückgabewert

**true** wenn das [XPathNavigator](../) erfolgreich zum Attribut wechselt; andernfalls **false**. Wenn **false**, bleibt die Position des [XPathNavigator](../) unverändert.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)