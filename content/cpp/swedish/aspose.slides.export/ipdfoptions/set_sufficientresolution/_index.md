---
title: set_SufficientResolution()
second_title: Aspose.Slides för C++ API-referens
description: Anger ett värde som bestämmer upplösningen för bilder i PDF-dokumentet.
type: docs
weight: 326
url: /sv/aspose.slides.export/ipdfoptions/set_sufficientresolution/
---
## IPdfOptions::set_SufficientResolution(float) metod

Anger ett värde som bestämmer upplösningen för bilder i PDF-dokumentet.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SufficientResolution(float value)=0
```

## Anmärkningar

Egenskapen påverkar filstorlek, exporttid och bildkvalitet.

Standardvärdet är **96**.

Effekten av denna parameter beror på några faktorer. Algoritmen försöker få bästa möjliga utdata bildstorlek enligt egenskapsvärdet, källbildens storlek och bildramens storlek. Användning av liknande egenskapsvärden kan ge samma resultat. Det rekommenderas att använda steg 16 eller 32 för att få en märkbar effekt.

Skriv **float**.
## Se även

* Klass [IPdfOptions](../)
* Namnutrymme [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)