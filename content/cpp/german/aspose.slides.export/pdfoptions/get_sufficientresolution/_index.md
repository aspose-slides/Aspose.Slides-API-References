---
title: get_SufficientResolution()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen Wert zurück, der die Auflösung von Bildern im PDF-Dokument bestimmt.
type: docs
weight: 352
url: /de/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() Methode

Gibt einen Wert zurück, der die Auflösung von Bildern im PDF-Dokument bestimmt.

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## Anmerkungen

Die Eigenschaft wirkt sich auf die Dateigröße, die Exportzeit und die Bildqualität aus.

Der Standardwert ist **96**.

Der Effekt dieses Parameters hängt von wenigen Faktoren ab. Der Algorithmus versucht, die optimale Ausgabebildgröße entsprechend dem Eigenschaftswert, der Größe des Quellbildes und der Größe des Bildrahmens zu ermitteln. Die Verwendung ähnlicher Eigenschaftswerte kann dasselbe Ergebnis liefern. Es wird empfohlen, Schritte von 16 oder 32 zu verwenden, um einen sichtbaren Effekt zu erzielen.

Lese **float**. 
## Siehe auch

* Klasse [PdfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)