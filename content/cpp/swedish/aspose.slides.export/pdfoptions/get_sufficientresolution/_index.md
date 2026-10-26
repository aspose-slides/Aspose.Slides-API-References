---
title: get_SufficientResolution()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett värde som bestämmer upplösningen för bilder i PDF-dokumentet.
type: docs
weight: 352
url: /sv/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() metod


Returnerar ett värde som bestämmer upplösningen för bilder i PDF-dokumentet.

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## Anmärkningar


Egenskapen påverkar filstorleken, exporttiden och bildkvaliteten.

Standardvärdet är **96**.

Effekten av den här parametern beror på några faktorer. Algoritmen försöker få bästa möjliga bildstorlek enligt egenskapens värde, källbildens storlek och bildramens storlek. Användning av liknande egenskapsvärden kan ge samma resultat. Det rekommenderas att använda steg 16 eller 32 för att få en märkbar effekt.

Läs **float**. 
## Se även

* Klass [PdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)