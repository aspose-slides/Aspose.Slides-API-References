---
title: MoveToFirstNamespace()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, bewegt sie den XPathNavigator zum ersten Namensbereichsknoten, der dem angegebenen XPathNamespaceScope entspricht.
type: docs
weight: 560
url: /de/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) Methode

Wenn sie in einer abgeleiteten Klasse überschrieben wird, bewegt sie das [XPathNavigator](../) zum ersten Namensbereichsknoten, der dem angegebenen XPathNamespaceScope entspricht.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Ein XPathNamespaceScope-Wert, der den Namensbereichs-Scope beschreibt. |

### Rückgabewert

**true** wenn das [XPathNavigator](../) erfolgreich zum ersten Namensbereichsknoten verschoben wird; andernfalls **false**. Wenn **false**, bleibt die Position des [XPathNavigator](../) unverändert.

## XPathNavigator::MoveToFirstNamespace() Methode

Bewegt das [XPathNavigator](../) zum ersten Namensbereichsknoten des aktuellen Knotens.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### Rückgabewert

**true** wenn das [XPathNavigator](../) erfolgreich zum ersten Namensbereichsknoten verschoben wird; andernfalls **false**. Wenn **false**, bleibt die Position des [XPathNavigator](../) unverändert.

## Siehe Auch

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)