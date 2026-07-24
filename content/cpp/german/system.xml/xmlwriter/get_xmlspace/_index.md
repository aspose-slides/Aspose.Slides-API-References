---
title: get_XmlSpace()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wenn in einer abgeleiteten Klasse überschrieben, gibt ein XmlSpace zurück, das den aktuellen xml:space-Bereich darstellt."
type: docs
weight: 27
url: /de/system.xml/xmlwriter/get_xmlspace/
---
## XmlWriter::get_XmlSpace() Methode

When overridden in a derived class, gets an XmlSpace representing the current **xml:space** scope.

```cpp
virtual System::Xml::XmlSpace System::Xml::XmlWriter::get_XmlSpace()
```

### Rückgabewert

An XmlSpace representing the current **xml:space** scope.

| Wert | Bedeutung |
| --- | --- |
| `None`| Dies ist die Vorgabe, wenn kein `xml:space`-Bereich existiert. |
| `Default`| Der aktuelle Bereich ist `xml:space="default"`. |
| `Preserve`| Der aktuelle Bereich ist `xml:space="preserve"`. |

## Siehe auch

* Aufzählung [XmlSpace](../../xmlspace/)
* Klasse [XmlWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)