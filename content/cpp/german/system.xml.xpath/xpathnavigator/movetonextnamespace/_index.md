---
title: MoveToNextNamespace()
second_title: Aspose.Slides für C++ API-Referenz
description: Wird in einer abgeleiteten Klasse überschrieben, bewegt es den XPathNavigator zum nächsten Namensbereichsknoten, der dem angegebenen XPathNamespaceScope entspricht.
type: docs
weight: 573
url: /de/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) Methode


Wenn in einer abgeleiteten Klasse überschrieben, bewegt es das [XPathNavigator](../) zum nächsten Namensbereichsknoten, der den angegebenen XPathNamespaceScope entspricht.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Ein XPathNamespaceScope-Wert, der den Namensbereich beschreibt. |

### Rückgabewert

**true** wenn [XPathNavigator](../) erfolgreich zum nächsten Namensbereichsknoten bewegt wird; andernfalls **false**. Wenn **false**, bleibt die Position des [XPathNavigator](../) unverändert.

## XPathNavigator::MoveToNextNamespace() Methode


Bewegt das [XPathNavigator](../) zum nächsten Namensbereichsknoten.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```


### Rückgabewert

**true** wenn [XPathNavigator](../) erfolgreich zum nächsten Namensbereichsknoten bewegt wird; andernfalls **false**. Wenn **false**, bleibt die Position des [XPathNavigator](../) unverändert.

## Siehe auch

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)