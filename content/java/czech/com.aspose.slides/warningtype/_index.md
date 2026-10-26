---
title: WarningType
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje typ varování.
type: docs
url: /cs/com.aspose.slides/warningtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Reprezentuje typ varování.
## Pole

| Pole | Popis |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Byla ve zdrojovém dokumentu zjištěna chyba, která pravděpodobně způsobí, že dokument nebude možné otevřít, pokud bude uložen v původním formátu. |
| [DataLoss](#DataLoss) | Text/graf nebo jiná data budou po načtení dokumentu nebo po uložení vytvořeného dokumentu zcela chybět. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Ztráta hlavního formátování. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Menší ztráta formátování. |
| [CompatibilityIssue](#CompatibilityIssue) | Jedná se o známý problém, který zabrání otevření dokumentu v některých uživatelských agentech nebo v předchozích verzích uživatelských agentů. |
| [UnexpectedContent](#UnexpectedContent) | Nějaký obsah ve zdrojovém dokumentu nebyl rozpoznán (např. |
### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Byla ve zdrojovém dokumentu zjištěna chyba, která pravděpodobně způsobí, že dokument nebude možné otevřít, pokud bude uložen v původním formátu.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Text/graf nebo jiná data budou po načtení dokumentu nebo po uložení vytvořeného dokumentu zcela chybět.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Ztráta hlavního formátování.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Menší ztráta formátování.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Jedná se o známý problém, který zabrání otevření dokumentu v některých uživatelských agentech nebo v předchozích verzích uživatelských agentů.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Nějaký obsah ve zdrojovém dokumentu nebyl rozpoznán (např. není podporován), což může nebo nemusí způsobit problémy nebo vést ke ztrátě dat/formátování.