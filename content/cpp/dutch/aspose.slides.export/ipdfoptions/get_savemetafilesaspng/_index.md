---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides voor C++ API-referentie
description: True om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lees bool.
type: docs
weight: 287
url: /nl/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() methode


True om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lees **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Opmerkingen


Standaard is **true**. Een Pdf-document kan vectorgrafische afbeeldingen en rasterafbeeldingen bevatten. Als SaveMetafilesAsPng is ingesteld op true, wordt de bron-Metafile-afbeelding omgezet naar Png-formaat en opgeslagen in Pdf als een rasterafbeelding. Als SaveMetafilesAsPng is ingesteld op false, wordt de bron-Metafile omgezet naar Pdf-vectorgrafieken. Elke aanpak heeft voor- en nadelen. Bijvoorbeeld, als Metafile wordt omgezet naar PNG, kan er kwaliteitsverlies optreden tijdens het schalen van het resulterende document. Als Metafile wordt omgezet naar Pdf-vectorgrafieken, kunnen prestatieproblemen in de Pdf-viewer mogelijk zijn. 
## Zie ook

* Klasse [IPdfOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)