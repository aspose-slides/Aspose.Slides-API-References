---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides för C++ API-referens
description: True för att konvertera alla metafiler som används i en presentation till PNG-bilder. Skriv bool.
type: docs
weight: 339
url: /sv/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) metod


True för att konvertera alla metafiler som används i en presentation till PNG-bilder. Skriv **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Anmärkningar


Standard är **true**. Pdf-dokument kan innehålla vektorgrafik och rasterbilder. Om SaveMetafilesAsPng är satt till true konverteras källmetafilbilden till Png-format och sparas i Pdf som en rasterbild. Om SaveMetafilesAsPng är satt till false konverteras källmetafil till Pdf-vektorgrafik. Varje tillvägagångssätt har fördelar och nackdelar. Till exempel, om Metafile konverteras till PNG, kan viss kvalitetsförlust uppstå vid skalning av det resulterande dokumentet. Om Metafile konverteras till Pdf-vektorgrafik, kan prestandaproblem i Pdf-visningsverktyg uppstå. 

## Se även

* Klass [PdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)