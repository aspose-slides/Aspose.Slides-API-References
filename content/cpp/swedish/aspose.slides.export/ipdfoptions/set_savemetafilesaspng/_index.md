---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides för C++ API-referens
description: Sant för att konvertera alla metafiler som används i en presentation till PNG-bilderna. Skriv bool.
type: docs
weight: 300
url: /sv/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) metod

Sant för att konvertera alla metafiler som används i en presentation till PNG-bilderna. Skriv **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Anmärkningar

Standardvärdet är **true**. Pdf-dokument kan innehålla vektorgrafik och rasterbilder. Om SaveMetafilesAsPng är satt till true konverteras käll-Metafile-bilden till Png-format och sparas i Pdf som en rasterbild. Om SaveMetafilesAsPng är satt till false konverteras käll-Metafile till Pdf-vektorgrafik. Varje tillvägagångssätt har fördelar och nackdelar. Till exempel, om Metafile konverteras till PNG, kan viss kvalitetsförlust uppstå vid skalning av det resulterande dokumentet. Om Metafile konverteras till Pdf-vektorgrafik, kan prestandaproblem i Pdf-visningsverktyg uppstå.

## Se även

* Klass [IPdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)