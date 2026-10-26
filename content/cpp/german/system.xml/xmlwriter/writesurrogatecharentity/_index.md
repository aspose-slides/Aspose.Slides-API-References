---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, erzeugt und schreibt es die Surrogat-Zeichen-Entität für das Surrogat-Zeichenpaar.
type: docs
weight: 261
url: /de/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) Methode


Wird in einer abgeleiteten Klasse überschrieben, erzeugt und schreibt es die Surrogatzeichen-Entität für das Surrogatzeichenpaar.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lowChar | char16_t | Der niederwertige Surrogat. Dies muss ein Wert zwischen 0xDC00 und 0xDFFF sein. |
| highChar | char16_t | Der hochwertige Surrogat. Dies muss ein Wert zwischen 0xD800 und 0xDBFF sein. |

## Siehe Auch

* Klasse [XmlWriter](../)
* Namespace [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)