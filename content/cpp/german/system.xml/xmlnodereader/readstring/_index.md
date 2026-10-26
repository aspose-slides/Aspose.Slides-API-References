---
title: ReadString()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest den Inhalt eines Elements oder Textknotens als Zeichenfolge.
type: docs
weight: 391
url: /de/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() Methode


Liest den Inhalt eines Elements oder Textknotens als Zeichenfolge.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```


### Rückgabewert

Der Inhalt des Elements oder des textähnlichen Knotens (Dies kann CDATA, [Text](../../../system.text/)-Knoten und so weiter umfassen). Dies kann ein leerer String sein, wenn der Reader auf etwas anderes als ein Element- oder Textknoten positioniert ist oder wenn kein weiterer Textinhalt im aktuellen Kontext zurückgegeben werden kann. Hinweis: Der Textknoten kann entweder ein Element- oder ein Attribut-Textknoten sein.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)