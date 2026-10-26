---
title: InsertElementAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Geschwisterelement nach dem aktuellen Knoten unter Verwendung des angegebenen Namensraumpräfixes, des lokalen Namens und des angegebenen Namensraum-URI, mit dem angegebenen Wert.
type: docs
weight: 1028
url: /de/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) Methode

Erstellt ein neues Geschwisterelement nach dem aktuellen Knoten unter Verwendung des angegebenen Namensraumpräfixes, des lokalen Namens und des angegebenen Namensraum-URI, mit dem angegebenen Wert.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Der Namensraumpräfix des neuen Kind-Elements (falls vorhanden). |
| localName | [String](../../../system/string/) | Der lokale Name des neuen Kind-Elements (falls vorhanden). |
| namespaceURI | [String](../../../system/string/) | Der Namensraum-URI des neuen Kind-Elements (falls vorhanden). [String::Empty](../../../system/string/empty/) und **nullptr** sind gleichwertig. |
| value | [String](../../../system/string/) | Der Wert des neuen Kind-Elements. Wenn [String::Empty](../../../system/string/empty/) oder **nullptr** übergeben werden, wird ein leeres Element erstellt. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)