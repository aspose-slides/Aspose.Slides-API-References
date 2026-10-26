---
title: set_SufficientResolution()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt einen Wert fest, der die Auflösung von Bildern im PDF-Dokument bestimmt.
type: docs
weight: 365
url: /de/aspose.slides.export/pdfoptions/set_sufficientresolution/
---
## PdfOptions::set_SufficientResolution(float) Methode

Legt einen Wert fest, der die Auflösung von Bildern im PDF-Dokument bestimmt.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SufficientResolution(float value) override
```

## Anmerkungen

Die Eigenschaft wirkt sich auf die Dateigröße, die Exportzeit und die Bildqualität aus.

Der Standardwert ist **96**.

Der Effekt dieses Parameters hängt von wenigen Faktoren ab. Der Algorithmus versucht, die beste Ausgabebildgröße entsprechend dem Eigenschaftswert, der Quellbildgröße und der Bildrahmengröße zu erhalten. Die Verwendung ähnlicher Eigenschaftswerte kann das gleiche Ergebnis liefern. Es wird empfohlen, einen Schritt von 16 oder 32 zu verwenden, um einen sichtbaren Effekt zu erzielen.

Schreiben **float**. 
## Siehe auch

* Klasse [PdfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)