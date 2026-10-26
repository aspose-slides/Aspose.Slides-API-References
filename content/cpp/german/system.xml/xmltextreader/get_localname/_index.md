---
title: get_LocalName()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den lokalen Namen des aktuellen Knotens zurück.
type: docs
weight: 27
url: /de/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName() Methode


Gibt den lokalen Namen des aktuellen Knotens zurück.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```


### Rückgabewert

Der Name des aktuellen Knotens ohne das Präfix. Zum Beispiel ist **LocalName** **book** für das Element **<bk:book>**. Für Knotentypen, die keinen Namen haben (wie **[Text](../../../system.text/)**, **Comment** und so weiter), gibt diese Methode [String::Empty](../../../system/string/empty/) zurück.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)