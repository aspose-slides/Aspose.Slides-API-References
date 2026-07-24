---
title: GetAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert des Attributs mit dem angegebenen lokalen Namen und dem Namespace-URI zurück.
type: docs
weight: 482
url: /de/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) Methode

Gibt den Wert des Attributs mit dem angegebenen lokalen Namen und dem Namespace-URI zurück.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. **localName** ist case-sensitive. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

Ein [String](../../../system/string/), das den Wert des angegebenen Attributs enthält; [String::Empty](../../../system/string/empty/) falls kein passendes Attribut gefunden wird oder wenn der [XPathNavigator](../) nicht auf einem Elementknoten positioniert ist.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)