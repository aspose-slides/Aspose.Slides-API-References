---
title: get_JpegQuality()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. Läs uint8_t.
type: docs
weight: 79
url: /sv/aspose.slides.export/ihtmloptions/get_jpegquality/
---
## IHtmlOptions::get_JpegQuality() metod


Returnerar ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. Läs **uint8_t**.

```cpp
virtual uint8_t Aspose::Slides::Export::IHtmlOptions::get_JpegQuality()=0
```

## Anmärkningar


Har effekt endast när ett dokument innehåller JPEG-bilder.

Använd den här egenskapen för att hämta eller ange kvaliteten på bilderna i ett dokument vid sparande i PDF-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal kompression och 100 betyder bästa kvalitet men minimal kompression.

Standardvärdet är **95**.
## Se även

* Klass [IHtmlOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)