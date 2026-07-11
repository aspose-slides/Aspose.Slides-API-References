---
title: WarningType
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет тип предупреждения.
type: docs
url: /ru/com.aspose.slides/warningtype/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Представляет тип предупреждения.
## Поля

| Поле | Описание |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Обнаружена проблема в исходном документе, из-за которой очень вероятно, что документ не сможет быть открыт, если его сохранить в оригинальном формате. |
| [DataLoss](#DataLoss) | Текст/диаграмма/изображение или другие данные будут полностью отсутствовать либо в дереве документа после загрузки, либо в созданном документе после сохранения. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Крупная потеря форматирования. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Незначительная потеря форматирования. |
| [CompatibilityIssue](#CompatibilityIssue) | Это известная проблема, которая предотвратит открытие документа некоторыми пользовательскими агентами или их предыдущими версиями. |
| [UnexpectedContent](#UnexpectedContent) | Некоторое содержимое в исходном документе не может быть распознано (т.е. |
### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```


Обнаружена проблема в исходном документе, из-за которой очень вероятно, что документ не сможет быть открыт, если его сохранить в оригинальном формате.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```


Текст/диаграмма/изображение или другие данные будут полностью отсутствовать либо в дереве документа после загрузки, либо в созданном документе после сохранения.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```


Крупная потеря форматирования.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```


Незначительная потеря форматирования.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```


Это известная проблема, которая предотвратит открытие документа некоторыми пользовательскими агентами или их предыдущими версиями.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```


Некоторое содержимое в исходном документе не может быть распознано (т. е. не поддерживается), это может привести к проблемам или к потере данных/форматирования.