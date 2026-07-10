---
title: WarningType
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示一种警告类型。
type: docs
url: /zh/com.aspose.slides/warningtype/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

表示一种警告类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | 在源文档中检测到问题，这使得文档在以原始格式保存后很可能无法打开。 |
| [DataLoss](#DataLoss) | 文本、图表、图像或其他数据将在加载后文档树中，或保存后创建的文档中完全缺失。 |
| [MajorFormattingLoss](#MajorFormattingLoss) | 严重的格式丢失。 |
| [MinorFormattingLoss](#MinorFormattingLoss) | 轻微的格式丢失。 |
| [CompatibilityIssue](#CompatibilityIssue) | 这是已知问题，会导致某些用户代理或其早期版本无法打开文档。 |
| [UnexpectedContent](#UnexpectedContent) | 源文档中的某些内容无法识别（即 |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

在源文档中检测到问题，这使得文档在以原始格式保存后很可能无法打开。

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

文本、图表、图像或其他数据将在加载后文档树中，或保存后创建的文档中完全缺失。

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

严重的格式丢失。

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

轻微的格式丢失。

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

这是已知问题，会导致某些用户代理或其早期版本无法打开文档。

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

源文档中的某些内容无法识别（即不受支持），这可能导致问题，也可能导致数据/格式丢失。