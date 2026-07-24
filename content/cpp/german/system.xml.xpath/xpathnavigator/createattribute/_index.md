---
title: CreateAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen Attributknoten im aktuellen Elementknoten unter Verwendung des angegebenen Namensraumpräfixes, des lokalen Namens und des angegebenen Namensraum-URI mit dem angegebenen Wert.
type: docs
weight: 1041
url: /de/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) Methode

Erstellt einen Attributknoten im aktuellen Elementknoten unter Verwendung des angegebenen Namensraumpräfixes, des lokalen Namens und des Namensraum-URI mit dem angegebenen Wert.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Der Namensraumpräfix des neuen Attributknotens (falls vorhanden). |
| localName | [String](../../../system/string/) | Der lokale Name des neuen Attributknotens, der nicht [String::Empty](../../../system/string/empty/) oder **nullptr** sein darf. |
| namespaceURI | [String](../../../system/string/) | Der Namensraum-URI für den neuen Attributknoten (falls vorhanden). |
| value | [String](../../../system/string/) | Der Wert des neuen Attributknotens. Wenn [String::Empty](../../../system/string/empty/) oder **nullptr** übergeben werden, wird ein leerer Attributknoten erstellt. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)