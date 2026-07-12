---
title: WarningType
second_title: Aspose.Slides for Android Java API hivatkozás
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
| [SourceFileCorruption](#SourceFileCorruption) | A forrásdokumentumban egy problémát észleltek, ami nagyon valószínűvé teszi, hogy a dokumentum nem lesz megnyitható, ha az eredeti formátumban van mentve. |
| [DataLoss](#DataLoss) | A szöveg/grafikon/kép vagy egyéb adatok teljesen hiányozni fognak akár a betöltés után a dokumentumfa struktúrájából, akár a mentés után a létrehozott dokumentumból. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Komoly formázási veszteség. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Kisebb formázási veszteség. |
| [CompatibilityIssue](#CompatibilityIssue) | Ez egy ismert probléma, amely megakadályozza a dokumentum megnyitását bizonyos felhasználói ügynökök vagy a régebbi verziók számára. |
| [UnexpectedContent](#UnexpectedContent) | A forrásdokumentum egyes tartalmait nem lehetett felismerni (pl. |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

A forrásdokumentumban egy problémát észleltek, ami nagyon valószínűvé teszi, hogy a dokumentum nem lesz megnyitható, ha az eredeti formátumban van mentve.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

A szöveg/grafikon/kép vagy egyéb adatok teljesen hiányozni fognak akár a betöltés után a dokumentumfa struktúrájából, akár a mentés után a létrehozott dokumentumból.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Komoly formázási veszteség.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Kisebb formázási veszteség.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Ez egy ismert probléma, amely megakadályozza a dokumentum megnyitását bizonyos felhasználói ügynökök vagy a régebbi verziók számára.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

A forrásdokumentum egyes tartalmait nem lehetett felismerni (pl. nem támogatott), ez okozhat problémákat vagy adat-/formázásvesztéshez vezethet.