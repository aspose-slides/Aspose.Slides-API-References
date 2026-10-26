---
title: get_SufficientResolution()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen Wert zurück, der die Auflösung von Bildern im PDF-Dokument bestimmt.
type: docs
weight: 313
url: /de/aspose.slides.export/ipdfoptions/get_sufficientresolution/
---
## IPdfOptions::get_SufficientResolution() Methode


Gibt einen Wert zurück, der die Auflösung von Bildern im PDF-Dokument bestimmt.

```cpp
virtual float Aspose::Slides::Export::IPdfOptions::get_SufficientResolution()=0
```

## Bemerkungen


Die Eigenschaft wirkt sich auf die Dateigröße, die Exportzeit und die Bildqualität aus.

Der Standardwert ist **96**.

Die Wirkung dieses Parameters hängt von einigen Faktoren ab. Der Algorithmus versucht, die optimale Ausgabebildgröße basierend auf dem Eigenschaftswert, der Größe des Quellbildes und der Bildrahmengröße zu ermitteln. Die Verwendung ähnlicher Eigenschaftswerte kann dasselbe Ergebnis liefern. Es wird empfohlen, Schritte von 16 oder 32 zu verwenden, um einen sichtbaren Effekt zu erzielen.

Lesen **float**. 
## Siehe auch

* Klasse [IPdfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)