---
title: WarningType
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a type of warning.
type: docs
weight: 610
url: /java/com.aspose.slides/warningtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Represents a type of warning.
## Constructors

| Constructor | Description |
| --- | --- |
| [WarningType()](#WarningType--) |  |
## Fields

| Field | Description |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | An issue has been detected in the source document which makes it very likely the document will be not be able to be opened if saved in it's original format. |
| [DataLoss](#DataLoss) | Text/chart/image or other data will be completely missing from either the document tree following load, or the created document following save. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Major formatting loss. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Minor formatting loss. |
| [CompatibilityIssue](#CompatibilityIssue) | This is known issue that will prevent the document being opened by certain user agents, or previous versions of user agents. |
| [UnexpectedContent](#UnexpectedContent) | Some content in the source document could not be recognised (i.e. is unsupported), this may or may not cause issues or result in data/formatting loss. |
### WarningType() {#WarningType--}
```
private WarningType()
```


### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```


An issue has been detected in the source document which makes it very likely the document will be not be able to be opened if saved in it's original format.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```


Text/chart/image or other data will be completely missing from either the document tree following load, or the created document following save.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```


Major formatting loss.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```


Minor formatting loss.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```


This is known issue that will prevent the document being opened by certain user agents, or previous versions of user agents.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```


Some content in the source document could not be recognised (i.e. is unsupported), this may or may not cause issues or result in data/formatting loss.

