---
title: get_LocalName()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, gibt sie den lokalen Namen des aktuellen Knotens zurück.
type: docs
weight: 40
url: /de/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() Methode


Wenn sie in einer abgeleiteten Klasse überschrieben wird, gibt sie den lokalen Namen des aktuellen Knotens zurück.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Rückgabewert

Der Name des aktuellen Knotens ohne das Präfix. Zum Beispiel ist **LocalName** **book** für das Element **<bk:book>**. Für Knotentypen, die keinen Namen haben (wie **[Text](../../../system.text/)**, **Comment** und so weiter), gibt diese Methode [String::Empty](../../../system/string/empty/) zurück.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)