---
title: Zip64Mode
second_title: Aspose.Slides för C++ API-referens
description: Anger när ZIP64-formatutökningar ska användas för OpenXML-fil.
type: docs
weight: 1119
url: /sv/aspose.slides.export/zip64mode/
---
## Zip64Mode enum

Anger när ZIP64-formatutökningar ska användas för OpenXML-fil.

```cpp
enum class Zip64Mode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Never | 0 | Använd inte ZIP64-formatutökningar. |
| IfNecessary | 1 | Använd ZIP64-formatutökningar om nödvändigt. |
| Always | 2 | Använd alltid ZIP64-formatutökningar. |

## Anmärkningar

OpenXML-fil är ett ZIP-arkiv som har en gräns på 4 GB (2^32 byte) för okomprimerad filstorlek, komprimerad filstorlek och den totala storleken på arkivet, samt en gräns på 65 535 (2^16-1) filer i arkivet. ZIP64-formatutökningar ökar gränserna till 2^64.

## Se även

* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)