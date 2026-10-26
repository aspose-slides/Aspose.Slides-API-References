---
title: set_SufficientResolution()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett värde som bestämmer upplösningen på bilder i PDF-dokumentet.
type: docs
weight: 365
url: /sv/aspose.slides.export/pdfoptions/set_sufficientresolution/
---
## PdfOptions::set_SufficientResolution(float) metod


Ställer in ett värde som bestämmer upplösningen på bilder i PDF-dokumentet.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SufficientResolution(float value) override
```

## Anmärkningar


Egenskapen påverkar filstorlek, exporttid och bildkvalitet.

Standardvärdet är **96**.

Effekten av denna parameter beror på några faktorer. Algoritmen försöker få den bästa utdata bildstorleken enligt egenskapens värde, källbildens storlek och bildramens storlek. Användning av liknande egenskapsvärden kan ge samma resultat. Det rekommenderas att använda steg 16 eller 32 för att få synlig effekt.

Skriv **float**. 
## Se också

* Klass [PdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)