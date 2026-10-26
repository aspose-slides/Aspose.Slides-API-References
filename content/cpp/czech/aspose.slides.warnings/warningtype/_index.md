---
title: WarningType
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje typ varování.
type: docs
weight: 92
url: /cs/aspose.slides.warnings/warningtype/
---
## enum WarningType

Reprezentuje typ varování.

```cpp
enum class WarningType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| SourceFileCorruption | 0 | Byl zjištěn problém ve zdrojovém dokumentu, což velmi pravděpodobně způsobí, že dokument nebude možné otevřít, pokud bude uložen v jeho původním formátu. |
| DataLoss | 1 | Text/graf/obrázek nebo jiná data budou zcela chybět buď ve stromu dokumentu po načtení, nebo ve vytvořeném dokumentu po uložení. |
| MajorFormattingLoss | 2 | Vážná ztráta formátování. |
| MinorFormattingLoss | 3 | Menší ztráta formátování. |
| CompatibilityIssue | 4 | Jedná se o známý problém, který zabrání otevření dokumentu některými uživatelskými agenty nebo předchozími verzemi uživatelských agentů. |
| UnexpectedContent | 99 | Nějaký obsah ve zdrojovém dokumentu nebylo možné rozpoznat (tj. není podporován), což může nebo nemusí způsobit problémy nebo vést ke ztrátě dat/formátování. |

## Viz také

* Jmenný prostor [Aspose::Slides::Warnings](../)
* Knihovna [Aspose.Slides](../../)