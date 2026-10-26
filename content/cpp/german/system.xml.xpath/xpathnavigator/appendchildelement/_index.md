---
title: AppendChildElement()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Kind-Elementknoten am Ende der Liste der Kindknoten des aktuellen Knotens unter Verwendung des Namespace-Präfixes, des lokalen Namens und des Namespace-URI, die mit dem angegebenen Wert angegeben sind.
type: docs
weight: 1002
url: /de/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) Methode

Erstellt einen neuen Kind-Elementknoten am Ende der Liste der Kindknoten des aktuellen Knotens unter Verwendung des Namespace-Präfixes, des lokalen Namens und des Namespace-URI, die mit dem angegebenen Wert angegeben sind.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Das Namespace-Präfix des neuen Kind-Elementknotens (falls vorhanden). |
| localName | [String](../../../system/string/) | Der lokale Name des neuen Kind-Elementknotens (falls vorhanden). |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des neuen Kind-Elementknotens (falls vorhanden). [String::Empty](../../../system/string/empty/) und **nullptr** sind äquivalent. |
| value | [String](../../../system/string/) | Der Wert des neuen Kind-Elementknotens. Wenn [String::Empty](../../../system/string/empty/) oder **nullptr** übergeben werden, wird ein leeres Element erstellt. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)