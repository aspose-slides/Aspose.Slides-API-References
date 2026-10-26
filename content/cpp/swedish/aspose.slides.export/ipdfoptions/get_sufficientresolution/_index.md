---
title: get_SufficientResolution()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett värde som bestämmer upplösningen för bilder i PDF-dokumentet.
type: docs
weight: 313
url: /sv/aspose.slides.export/ipdfoptions/get_sufficientresolution/
---
## IPdfOptions::get_SufficientResolution() metod


Returnerar ett värde som bestämmer upplösningen för bilder i PDF-dokumentet.

```cpp
virtual float Aspose::Slides::Export::IPdfOptions::get_SufficientResolution()=0
```

## Anmärkningar


Egenskapen påverkar filstorlek, exporttid och bildkvalitet.

Standardvärdet är **96**.

Effekten av denna parameter beror på några faktorer. Algoritmen försöker få bästa möjliga utskriftsbildstorlek utifrån egenskapens värde, källbildens storlek och bildramens storlek. Användning av liknande egenskapsvärden kan ge samma resultat. Rekommenderas att använda steg 16 eller 32 för att se en märkbar effekt.

Läs **float**. 
## Se även

* Klass [IPdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)