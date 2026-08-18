---
title: WarningType
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje typ ostrzeżenia.
type: docs
url: /pl/com.aspose.slides/warningtype/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Reprezentuje typ ostrzeżenia.
## Pola

| Pole | Opis |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Wykryto problem w dokumencie źródłowym, który bardzo prawdopodobnie uniemożliwi otwarcie dokumentu po zapisaniu w jego oryginalnym formacie. |
| [DataLoss](#DataLoss) | Tekst, wykres, obraz lub inne dane będą całkowicie brakować zarówno w drzewie dokumentu po wczytaniu, jak i w utworzonym dokumencie po zapisaniu. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Znaczna utrata formatowania. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Drobna utrata formatowania. |
| [CompatibilityIssue](#CompatibilityIssue) | Jest to znany problem, który uniemożliwi otwarcie dokumentu przez niektóre przeglądarki lub starsze wersje przeglądarek. |
| [UnexpectedContent](#UnexpectedContent) | Niektóre treści w dokumencie źródłowym nie mogły zostać rozpoznane (i.e. |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Wykryto problem w dokumencie źródłowym, który bardzo prawdopodobnie uniemożliwi otwarcie dokumentu po zapisaniu w jego oryginalnym formacie.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Tekst, wykres, obraz lub inne dane będą całkowicie brakować zarówno w drzewie dokumentu po wczytaniu, jak i w utworzonym dokumencie po zapisaniu.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Znaczna utrata formatowania.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Drobna utrata formatowania.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Jest to znany problem, który uniemożliwi otwarcie dokumentu przez niektóre przeglądarki lub starsze wersje przeglądarek.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Niektóre treści w dokumencie źródłowym nie mogły zostać rozpoznane (i.e. is unsupported), to może, ale nie musi, powodować problemy lub skutkować utratą danych/formatowania.