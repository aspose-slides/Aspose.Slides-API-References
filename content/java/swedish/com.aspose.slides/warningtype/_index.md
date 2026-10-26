---
title: WarningType
second_title: Aspose.Slides för Java API-referens
description: Representerar en typ av varning.
type: docs
url: /sv/com.aspose.slides/warningtype/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Representerar en typ av varning.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Ett problem har upptäckts i källdokumentet som gör det mycket sannolikt att dokumentet inte kan öppnas om det sparas i sitt ursprungliga format. |
| [DataLoss](#DataLoss) | Text/diagram/bild eller annan data kommer att vara helt saknad antingen i dokumentträdet efter inläsning eller i det skapade dokumentet efter sparning. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Större formateringsförlust. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Mindre formateringsförlust. |
| [CompatibilityIssue](#CompatibilityIssue) | Detta är ett känt problem som kommer att hindra dokumentet från att öppnas av vissa användaragenter eller tidigare versioner av användaragenter. |
| [UnexpectedContent](#UnexpectedContent) | Viss innehåll i källdokumentet kunde inte identifieras (t.ex. |
### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Ett problem har upptäckts i källdokumentet som gör det mycket sannolikt att dokumentet inte kan öppnas om det sparas i sitt ursprungliga format.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Text/diagram/bild eller annan data kommer att vara helt saknad antingen i dokumentträdet efter inläsning eller i det skapade dokumentet efter sparning.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Större formateringsförlust.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Mindre formateringsförlust.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Detta är ett känt problem som kommer att hindra dokumentet från att öppnas av vissa användaragenter eller tidigare versioner av användaragenter.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Viss innehåll i källdokumentet kunde inte identifieras (t.ex. är ej stödjat), detta kan eller kanske inte orsaka problem eller leda till data-/formateringsförlust.