---
title: CompressionLevel
second_title: Aspose.Slides för C++ API-referens
description: Anger ZIP-komprimeringsnivåer för OpenXML-fil. Högre nivåer ger bättre komprimering på bekostnad av långsammare bearbetning.
type: docs
weight: 846
url: /sv/aspose.slides.export/compressionlevel/
---
## CompressionLevel enum


Anger ZIP-komprimeringsnivåer för OpenXML-fil. Högre nivåer ger bättre komprimering på bekostnad av långsammare bearbetning.

```cpp
enum class CompressionLevel
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Ingen komprimering tillämpas. Filer lagras som de är. |
| Level1 | 1 | Snabbast komprimering med den lägsta komprimeringsgrad. |
| Level2 | 2 | Snabbare komprimering med något bättre komprimeringsgrad än [CompressionLevel::Level1](./). |
| Level3 | 3 | Ger bättre komprimering än [CompressionLevel::Level2](./) med måttlig prestandapåverkan. |
| Level4 | 4 | Ger bättre komprimering än [CompressionLevel::Level3](./). |
| Level5 | 5 | Ger förbättrad komprimering jämfört med [CompressionLevel::Level4](./) med extra behandlingstid. |
| Level6 | 6 | Standardkomprimering som erbjuder en bra balans mellan komprimeringshastighet och filstorlek. Standardkomprimeringsnivån. |
| Level7 | 7 | Ger högre komprimering än [CompressionLevel::Level6](./) med långsammare behandling. |
| Level8 | 8 | Ger högre komprimering än [CompressionLevel::Level7](./). |
| Level9 | 9 | Maximal komprimering. Producerar den minsta filstorleken med den långsammaste behandlingstiden. |

## Se även

* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)