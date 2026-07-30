---
title: CompressionLevel
second_title: Aspose.Slides pro C++ API Reference
description: Určuje úrovně ZIP komprese pro soubor OpenXML. Vyšší úrovně poskytují lepší kompresi za cenu pomalejšího zpracování.
type: docs
weight: 846
url: /cs/aspose.slides.export/compressionlevel/
---
## CompressionLevel výčet

Určuje úrovně ZIP komprese pro soubor OpenXML. Vyšší úrovně poskytují lepší kompresi za cenu pomalejšího zpracování.

```cpp
enum class CompressionLevel
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Komprese není aplikována. Soubory jsou uloženy beze změny. |
| Level1 | 1 | Nejrychlejší komprese s nejnižším kompresním poměrem. |
| Level2 | 2 | Rychlejší komprese s mírně lepším kompresním poměrem než [CompressionLevel::Level1](./). |
| Level3 | 3 | Poskytuje lepší kompresi než [CompressionLevel::Level2](./) s mírným dopadem na výkon. |
| Level4 | 4 | Poskytuje lepší kompresi než [CompressionLevel::Level3](./). |
| Level5 | 5 | Poskytuje vylepšenou kompresi oproti [CompressionLevel::Level4](./) s dalším časem zpracování. |
| Level6 | 6 | Standardní komprese, nabízející dobrý poměr mezi rychlostí komprese a velikostí souboru. Výchozí úroveň komprese. |
| Level7 | 7 | Poskytuje vyšší kompresi než [CompressionLevel::Level6](./) s pomalejším zpracováním. |
| Level8 | 8 | Poskytuje vyšší kompresi než [CompressionLevel::Level7](./). |
| Level9 | 9 | Maximální komprese. Vytváří nejmenší velikost souboru při nejpomalejším zpracování. |

## Viz také

* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)