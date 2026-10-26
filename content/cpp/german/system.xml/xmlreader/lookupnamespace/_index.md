---
title: LookupNamespace()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, löst sie ein Namespace-Präfix im Geltungsbereich des aktuellen Elements auf.
type: docs
weight: 729
url: /de/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) Methode

Wenn sie in einer abgeleiteten Klasse überschrieben wird, löst sie ein Namespace-Präfix im Geltungsbereich des aktuellen Elements auf.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Das Präfix, dessen Namespace-URI Sie auflösen möchten. Um den Standard-Namespace zu entsprechen, übergeben Sie eine leere Zeichenkette. |

### Rückgabewert

Der Namespace-URI, dem das Präfix zugeordnet ist, oder **nullptr**, wenn kein passendes Präfix gefunden wird.

## Siehe Auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)