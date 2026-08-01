---
title: CopyPixelOperation
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoe de bronkleur in een pixelkopieeroperatie wordt gecombineerd met de doelkleur om een eindkleur te verkrijgen.
type: docs
weight: 391
url: /nl/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum

Specificeert hoe de bronkleur in een pixelkopieeroperatie wordt gecombineerd met de doelkleur om een eindkleur te verkrijgen.

```cpp
enum class CopyPixelOperation
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| NoMirrorBitmap | n/a | De bitmap wordt niet gespiegeld. |
| Blackness | 66 | Het doelgebied wordt gevuld met de kleur met index 0 in het fysieke palet. |
| NotSourceErase | 1114278 | De bron- en doelkleuren worden ORed en de resulterende kleur wordt vervolgens geïnverteerd. |
| NotSourceCopy | 3342344 | Het brongebied wordt geïnverteerd en vervolgens gekopieerd naar het doel. |
| SourceErase | 4457256 | De geïnverteerde kleuren van het doelgebied worden ANDed met de kleuren van het brongebied. |
| DestinationInvert | 5570569 | Het doelgebied wordt geïnverteerd. |
| PatInvert | 5898313 | De kleuren van het momenteel geselecteerde penseel in de doelapparaatcontext worden XORed met de kleuren van het doel. |
| SourceInvert | 6684742 | De kleuren van de bron- en doelgebieden worden XORed. |
| SourceAnd | 8913094 | De kleuren van de bron- en doelgebieden worden ANDed. |
| MergePaint | 12255782 | De kleuren van het geïnverteerde brongebied worden ORed met de kleuren van het doelgebied. |
| MergeCopy | 12583114 | De kleuren van het brongebied worden ANDed met de kleuren van het geselecteerde penseel van de doelapparaatcontext. |
| SourceCopy | 13369376 | Het brongebied wordt direct gekopieerd naar het doelgebied. |
| SourcePaint | 15597702 | De kleuren van de bron- en doelgebieden worden ORed. |
| PatCopy | 15728673 | Het momenteel geselecteerde penseel in de doelapparaatcontext wordt gekopieerd naar de doelbitmap. |
| PatPaint | 16452105 | De kleuren van het momenteel geselecteerde penseel in de doelapparaatcontext worden ORed met de kleuren van het geïnverteerde brongebied. Het resultaat van deze operatie wordt ORed met de kleuren van het doelgebied. |
| Whiteness | 16711778 | Het doelgebied wordt gevuld met de kleur met index 1 in het fysieke palet. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) die bovenop het venster van de applicatie zijn gelaagd, worden opgenomen in de resulterende afbeelding. |

## Zie ook

* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)