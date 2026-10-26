---
title: WarningType
second_title: Aspose.Slides for Java API referenciája
description: Egy figyelmeztetéstípust képvisel.
type: docs
url: /hu/com.aspose.slides/warningtype/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Egy figyelmeztetéstípust képvisel.
## Mezők

| Mező | Leírás |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Az eredeti dokumentumban egy probléma észlelhető, amely miatt nagyon valószínű, hogy a dokumentum nem lesz megnyitható, ha az eredeti formátumban mentik. |
| [DataLoss](#DataLoss) | A szöveg/grafikon/kép vagy egyéb adatok teljesen hiányozni fognak a dokumentumfa betöltése után, vagy a létrehozott dokumentum mentése után. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Súlyos formázási veszteség. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Kisebb formázási veszteség. |
| [CompatibilityIssue](#CompatibilityIssue) | Ez egy ismert probléma, amely megakadályozza a dokumentum megnyitását bizonyos felhasználói ügynökök vagy azok korábbi verziói által. |
| [UnexpectedContent](#UnexpectedContent) | A forrásdokumentumban egyes tartalmak nem ismerhetők fel (azaz |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Az eredeti dokumentumban egy probléma észlelhető, amely miatt nagyon valószínű, hogy a dokumentum nem lesz megnyitható, ha az eredeti formátumban mentik.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

A szöveg/grafikon/kép vagy egyéb adatok teljesen hiányozni fognak a dokumentumfa betöltése után, vagy a létrehozott dokumentum mentése után.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Súlyos formázási veszteség.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Kisebb formázási veszteség.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Ez egy ismert probléma, amely megakadályozza a dokumentum megnyitását bizonyos felhasználói ügynökök vagy azok korábbi verziói által.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

A forrásdokumentumban egyes tartalmak nem ismerhetők fel (azaz nem támogatottak), ez okozhat problémákat, vagy akár adat- vagy formázásveszteséghez is vezethet.