---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides voor C++ API-referentie
description: True om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lezen bool.
type: docs
weight: 326
url: /nl/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() methode

True om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lezen **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Opmerkingen

Standaard is **true**. Pdf-document kan vectorgraphics en rasterafbeeldingen bevatten. Als SaveMetafilesAsPng is ingesteld op true, wordt de bron Metafile-afbeelding geconverteerd naar Png-formaat en opgeslagen in Pdf als een rasterafbeelding. Als SaveMetafilesAsPng is ingesteld op false, wordt de bron Metafile geconverteerd naar Pdf-vectorgraphics. Elke aanpak heeft voordelen en nadelen. Bijvoorbeeld, als Metafile wordt geconverteerd naar PNG, kan er kwaliteitsverlies optreden tijdens het schalen van het resulterende document. Als Metafile wordt geconverteerd naar Pdf-vectorgraphics, kunnen prestatieproblemen in de Pdf-viewer optreden.

## Zie ook

* Klasse [PdfOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)