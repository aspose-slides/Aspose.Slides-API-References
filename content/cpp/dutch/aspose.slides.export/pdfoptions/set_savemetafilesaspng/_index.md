---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides voor C++ API-referentie
description: True om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Schrijf bool.
type: docs
weight: 339
url: /nl/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) methode

True om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Schrijf **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Opmerkingen

Standaard is **true**. Een Pdf-document kan vectorafbeeldingen en rasterafbeeldingen bevatten. Als SaveMetafilesAsPng is ingesteld op true, wordt de bron Metafile-afbeelding geconverteerd naar Png-formaat en opgeslagen in Pdf als een rasterafbeelding. Als SaveMetafilesAsPng is ingesteld op false, wordt de bron Metafile geconverteerd naar Pdf-vectorafbeeldingen. Elke benadering heeft voor- en nadelen. Bijvoorbeeld, als Metafile wordt geconverteerd naar PNG, kan er enige kwaliteitsverlies optreden tijdens het schalen van het resulterende document. Als Metafile wordt geconverteerd naar Pdf-vectorafbeeldingen, kunnen er prestatieproblemen optreden in de Pdf-weergave-tool.

## Zie ook

* Klasse [PdfOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)