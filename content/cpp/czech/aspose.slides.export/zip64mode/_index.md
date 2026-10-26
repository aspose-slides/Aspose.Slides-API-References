---
title: Zip64Mode
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, kdy použít rozšíření formátu ZIP64 pro soubor OpenXML.
type: docs
weight: 1119
url: /cs/aspose.slides.export/zip64mode/
---
## Zip64Mode enum

Určuje, kdy použít rozšíření formátu ZIP64 pro soubor OpenXML.

```cpp
enum class Zip64Mode
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Never | 0 | Nepoužívejte rozšíření formátu ZIP64. |
| IfNecessary | 1 | Použijte rozšíření formátu ZIP64, pokud je to nutné. |
| Always | 2 | Vždy používejte rozšíření formátu ZIP64. |

## Poznámky

Soubor OpenXML je ZIP archiv, který má limit 4 GB (2^32 bajtů) na nekomprimovanou velikost souboru, komprimovanou velikost souboru a celkovou velikost archivu, stejně jako limit 65,535 (2^16-1) souborů v archivu. Rozšíření formátu ZIP64 zvyšují limity na 2^64. 

## Viz také

* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)