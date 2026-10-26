---
title: WarningType
second_title: Ссылка на API Aspose.Slides для Java
description: Представляет тип предупреждения.
type: docs
url: /ru/com.aspose.slides/warningtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Представляет тип предупреждения.
## Поля

| Поле | Описание |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | В исходном документе обнаружена проблема, из-за которой очень вероятно, что документ нельзя будет открыть, если сохранить его в its original format. |
| [DataLoss](#DataLoss) | Текст/диаграмма/изображение или другие данные будут полностью отсутствовать либо в дереве документа после загрузки, либо в созданном документе после сохранения. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Существенная потеря форматирования. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Незначительная потеря форматирования. |
| [CompatibilityIssue](#CompatibilityIssue) | Это известная проблема, которая помешает открыть документ некоторыми пользовательскими агентами или их предыдущими версиями. |
| [UnexpectedContent](#UnexpectedContent) | Некоторое содержимое исходного документа не удалось распознать (например, |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```


В исходном документе обнаружена проблема, из-за которой очень вероятно, что документ нельзя будет открыть, если сохранить его в its original format.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```


Текст/диаграмма/изображение или другие данные будут полностью отсутствовать либо в дереве документа после загрузки, либо в созданном документе после сохранения.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```


Существенная потеря форматирования.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```


Незначительная потеря форматирования.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```


Это известная проблема, которая помешает открыть документ некоторыми пользовательскими агентами или их предыдущими версиями.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```


Некоторое содержимое исходного документа не удалось распознать (например, is unsupported), this may or may not cause issues or result in data/formatting loss.