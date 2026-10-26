---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides för C++ API-referens
description: True för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs bool.
type: docs
weight: 326
url: /sv/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() method

True för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Anmärkningar

Standardvärdet är **true**. En Pdf-dokument kan innehålla vektorgrafik och rasterbilder. Om SaveMetafilesAsPng är satt till true konverteras käll-Metafile-bilden till Png-format och sparas i Pdf som en rasterbild. Om SaveMetafilesAsPng är satt till false konverteras käll-Metafile till Pdf-vektorgrafik. Varje tillvägagångssätt har fördelar och nackdelar. Till exempel, om Metafile konverteras till PNG kan viss kvalitetsförlust uppstå vid skalning av det resulterande dokumentet. Om Metafile konverteras till Pdf-vektorgrafik kan prestandaproblem i Pdf-visningsverktyget uppstå.

## Se även

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)