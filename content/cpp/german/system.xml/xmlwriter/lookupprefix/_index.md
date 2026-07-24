---
title: LookupPrefix()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, gibt sie das dem aktuellen Namespace-Scope am nächsten liegende Präfix für die Namespace-URI zurück.
type: docs
weight: 352
url: /de/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix(String) Methode

Wenn in einer abgeleiteten Klasse überschrieben, gibt die Methode das dem aktuellen Namespace-Scope am nächsten liegende Präfix für die Namespace-URI zurück.

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ns | [String](../../../system/string/) | Die Namespace-URI, deren Präfix Sie finden möchten. |

### Rückgabewert

Das passende Präfix oder **nullptr**, falls im aktuellen Scope keine passende Namespace-URI gefunden wird.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)