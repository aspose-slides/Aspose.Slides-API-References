---
title: WarningType
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en varningstyp.
type: docs
url: /sv/com.aspose.slides/warningtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Representerar en varningstyp.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Ett problem har upptäckts i källdokumentet vilket gör det mycket sannolikt att dokumentet inte kommer att kunna öppnas om det sparas i dess ursprungliga format. |
| [DataLoss](#DataLoss) | Text/diagram/bild eller annan data kommer att vara helt saknad från antingen dokumentträdet efter inläsning, eller det skapade dokumentet efter sparning. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Större formateringsförlust. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Mindre formateringsförlust. |
| [CompatibilityIssue](#CompatibilityIssue) | Detta är ett känt problem som kommer att förhindra att dokumentet kan öppnas av vissa användaragenter, eller tidigare versioner av användaragenter. |
| [UnexpectedContent](#UnexpectedContent) | Viss innehåll i källdokumentet kunde inte identifieras (t.ex. |
### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```


Ett problem har upptäckts i källdokumentet vilket gör det mycket sannolikt att dokumentet inte kommer att kunna öppnas om det sparas i dess ursprungliga format.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```


Text/diagram/bild eller annan data kommer att vara helt saknad från antingen dokumentträdet efter inläsning, eller det skapade dokumentet efter sparning.

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


Detta är ett känt problem som kommer att förhindra att dokumentet kan öppnas av vissa användaragenter, eller tidigare versioner av användaragenter.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```


Viss innehåll i källdokumentet kunde inte identifieras (t.ex. är inte stödd), detta kan eller kan inte orsaka problem eller leda till data-/formateringsförlust.