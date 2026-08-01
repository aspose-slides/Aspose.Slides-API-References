---
title: CompressionLevel
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert ZIP-compressieniveaus voor een OpenXML-bestand. Hogere niveaus bieden betere compressie ten koste van tragere verwerking.
type: docs
weight: 846
url: /nl/aspose.slides.export/compressionlevel/
---
## CompressionLevel enum

Specificeert ZIP-compressieniveaus voor een OpenXML-bestand. Hogere niveaus bieden betere compressie ten koste van tragere verwerking.

```cpp
enum class CompressionLevel
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Er wordt geen compressie toegepast. Bestanden worden onveranderd opgeslagen. |
| Level1 | 1 | Snelste compressie met de laagste compressieverhouding. |
| Level2 | 2 | Snellere compressie met iets betere compressieverhouding dan [CompressionLevel::Level1](./). |
| Level3 | 3 | Biedt betere compressie dan [CompressionLevel::Level2](./) met een matige impact op de prestaties. |
| Level4 | 4 | Biedt betere compressie dan [CompressionLevel::Level3](./). |
| Level5 | 5 | Biedt verbeterde compressie ten opzichte van [CompressionLevel::Level4](./) met extra verwerkingstijd. |
| Level6 | 6 | Standaardcompressie, die een goed evenwicht biedt tussen compressiesnelheid en bestandsgrootte. Het standaard compressieniveau. |
| Level7 | 7 | Biedt hogere compressie dan [CompressionLevel::Level6](./) met tragere verwerking. |
| Level8 | 8 | Biedt hogere compressie dan [CompressionLevel::Level7](./). |
| Level9 | 9 | Maximale compressie. Produceert de kleinste bestandsgrootte met de langzaamste verwerkingssnelheid. |

## Zie ook

* Namespace [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)