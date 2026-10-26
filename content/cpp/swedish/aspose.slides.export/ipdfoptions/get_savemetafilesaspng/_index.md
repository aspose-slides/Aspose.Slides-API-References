---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides för C++ API-referens
description: Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs bool.
type: docs
weight: 287
url: /sv/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() metod

Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Anmärkningar

Standard är **true**. Pdf-dokument kan innehålla vektorgrafik och rasterbilder. Om SaveMetafilesAsPng är satt till true konverteras käll-Metafile-bilden till Png-format och sparas i Pdf som en rasterbild. Om SaveMetafilesAsPng är satt till false konverteras käll-Metafile till Pdf-vektorgrafik. Varje tillvägagångssätt har fördelar och nackdelar. Till exempel, om Metafile konverteras till PNG, kan viss kvalitetsförlust uppstå vid skalning av det resulterande dokumentet. Om Metafile konverteras till Pdf-vektorgrafik, kan prestandaproblem i Pdf-visningsverktyg uppstå. 

## Se även

* Klass [IPdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)