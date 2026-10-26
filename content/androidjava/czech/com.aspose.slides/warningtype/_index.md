---
title: WarningType
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Reprezentuje typ varování.
type: docs
url: /cs/com.aspose.slides/warningtype/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Reprezentuje typ varování.
## Pole

| Pole | Popis |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Byl zjištěn problém ve zdrojovém dokumentu, který pravděpodobně způsobí, že dokument nebude možné otevřít, pokud bude uložen v původním formátu. |
| [DataLoss](#DataLoss) | Text/graf/obrázek nebo jiné údaje budou zcela chybět buď ve stromu dokumentu po načtení, nebo ve vytvořeném dokumentu po uložení. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Velká ztráta formátování. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Malá ztráta formátování. |
| [CompatibilityIssue](#CompatibilityIssue) | Jedná se o známý problém, který zabrání otevření dokumentu některými uživatelskými agenty nebo staršími verzemi uživatelských agentů. |
| [UnexpectedContent](#UnexpectedContent) | Nějaký obsah ve zdrojovém dokumentu nelze rozpoznat (např. |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Byl zjištěn problém ve zdrojovém dokumentu, který pravděpodobně způsobí, že dokument nebude možné otevřít, pokud bude uložen v původním formátu.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Text/graf/obrázek nebo jiné údaje budou zcela chybět buď ve stromu dokumentu po načtení, nebo ve vytvořeném dokumentu po uložení.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Velká ztráta formátování.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Malá ztráta formátování.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Jedná se o známý problém, který zabrání otevření dokumentu některými uživatelskými agenty nebo staršími verzemi uživatelských agentů.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Nějaký obsah ve zdrojovém dokumentu nelze rozpoznat (např. není podporován), což může nebo nemusí způsobit problémy nebo vést ke ztrátě dat/formátování.