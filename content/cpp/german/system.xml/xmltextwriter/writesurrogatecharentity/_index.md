---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides für C++ API-Referenz
description: Erzeugt und schreibt die Surrogat-Zeichenentität für das Surrogat-Zeichenpaar.
type: docs
weight: 391
url: /de/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) Methode

Erzeugt und schreibt die Surrogat-Zeichenentität für das Surrogat-Zeichenpaar.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lowChar | char16_t | Der Low-Surrogate. Dieser muss ein Wert zwischen **0xDC00** und **0xDFFF** sein. |
| highChar | char16_t | Der High-Surrogate. Dieser muss ein Wert zwischen **0xD800** und **0xDBFF** sein. |

## Siehe auch

* Klasse [XmlTextWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)