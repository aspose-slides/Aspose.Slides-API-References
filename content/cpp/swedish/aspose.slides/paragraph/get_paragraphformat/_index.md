---
title: get_ParagraphFormat()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar formateringsobjektet för detta stycke. Skrivskyddad IParagraphFormat.
type: docs
weight: 14
url: /sv/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() metod

Returnerar formateringsobjektet för detta stycke. Skrivskyddad [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Anmärkningar

Formateringsobjektet innehåller de formateringsparametrar som definierats för endast det aktuella stycket, ärvd data tillämpas inte.

För att få de effektiva värdena inklusive ärvda värden, använd [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/)-metoden.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IParagraphFormat](../../iparagraphformat/)
* Klass [Paragraph](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)