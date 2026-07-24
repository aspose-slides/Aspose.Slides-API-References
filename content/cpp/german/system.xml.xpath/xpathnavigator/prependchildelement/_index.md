---
title: PrependChildElement()
second_title: "Aspose.Slides für C++ API Referenz"
description: "Erstellt ein neues Kindelement am Anfang der Liste der Kindknoten des aktuellen Knotens unter Verwendung des Namensraumpräfixes, des lokalen Namens und der Namensraum-URI, die mit dem angegebenen Wert festgelegt wurden."
type: docs
weight: 989
url: /de/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) Methode

Erstellt ein neues Kindelement am Anfang der Liste der Kindknoten des aktuellen Knotens unter Verwendung des mit dem angegebenen Wert angegebenen Namensraumpräfixes, des lokalen Namens und der Namensraum-URI.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Der Namensraumpräfix des neuen Kindelements (falls vorhanden). |
| localName | [String](../../../system/string/) | Der lokale Name des neuen Kindelements (falls vorhanden). |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des neuen Kindelements (falls vorhanden). [String::Empty](../../../system/string/empty/) und **nullptr** sind äquivalent. |
| value | [String](../../../system/string/) | Der Wert des neuen Kindelements. Wenn [String::Empty](../../../system/string/empty/) oder **nullptr** übergeben werden, wird ein leeres Element erstellt. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)