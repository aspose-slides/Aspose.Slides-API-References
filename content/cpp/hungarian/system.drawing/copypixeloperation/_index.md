---
title: CopyPixelOperation
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogy egy pixelmásolási műveletben a forrás színe hogyan kombinálódik a cél színével, hogy végső színt eredményezzen.
type: docs
weight: 391
url: /hu/system.drawing/copypixeloperation/
---
## CopyPixelOperation enumeráció

Meghatározza, hogy egy pixelmásolási műveletben a forrás színe hogyan kombinálódik a cél színével, hogy végső színt eredményezzen.

```cpp
enum class CopyPixelOperation
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| NoMirrorBitmap | n/a | A bitmap nem tükröződik. |
| Blackness | 66 | A célterületet a fizikai palettában 0 indexű szín használatával tölti ki. |
| NotSourceErase | 1114278 | A forrás és cél színeket OR művelettel kombinálják, majd az eredmény színt invertálják. |
| NotSourceCopy | 3342344 | A forrás területet invertálják, majd átmásolják a célra. |
| SourceErase | 4457256 | A célterület invertált színeit AND művelettel kombinálják a forrás terület színeivel. |
| DestinationInvert | 5570569 | A célterület invertálva van. |
| PatInvert | 5898313 | A cél eszközkörnyezetben jelenleg kiválasztott ecset színeit XOR művelettel kombinálják a cél színeivel. |
| SourceInvert | 6684742 | A forrás és cél területek színeit XOR művelettel kombinálják. |
| SourceAnd | 8913094 | A forrás és cél területek színeit AND művelettel kombinálják. |
| MergePaint | 12255782 | Az invertált forrás terület színeit OR művelettel kombinálják a cél terület színeivel. |
| MergeCopy | 12583114 | A forrás terület színeit AND művelettel kombinálják a cél eszközkörnyezetben kiválasztott ecset színeivel. |
| SourceCopy | 13369376 | A forrás területet közvetlenül átmásolják a cél területre. |
| SourcePaint | 15597702 | A forrás és cél területek színeit OR művelettel kombinálják. |
| PatCopy | 15728673 | A cél eszközkörnyezetben jelenleg kiválasztott ecsetet átmásolják a cél bitmapre. |
| PatPaint | 16452105 | A cél eszközkörnyezetben jelenleg kiválasztott ecset színeit OR művelettel kombinálják az invertált forrás terület színeivel. Ennek az eredményét OR művelettel kombinálják a cél terület színeivel. |
| Whiteness | 16711778 | A célterületet a fizikai palettában 1-es indexű szín használatával tölti ki. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) amelyek az alkalmazásablak tetején vannak rétegelve, a keletkező képen megjelennek. |

## Lásd még

* Névtere [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)