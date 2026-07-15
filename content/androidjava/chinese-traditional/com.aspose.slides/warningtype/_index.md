---
title: WarningType
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示一種警告類型。
type: docs
url: /zh-hant/com.aspose.slides/warningtype/
---
**繼承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

代表一種警告類型。
## 欄位

| 欄位 | 說明 |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | 已在原始文件中偵測到問題，這使得若以原始格式儲存，文件很可能無法開啟。 |
| [DataLoss](#DataLoss) | 載入後的文件樹或儲存後產生的文件中，文字/圖表/影像或其他資料將會完全缺失。 |
| [MajorFormattingLoss](#MajorFormattingLoss) | 主要格式遺失。 |
| [MinorFormattingLoss](#MinorFormattingLoss) | 輕微格式遺失。 |
| [CompatibilityIssue](#CompatibilityIssue) | 這是一個已知問題，會阻止某些使用者代理或其舊版開啟文件。 |
| [UnexpectedContent](#UnexpectedContent) | 原始文件中的某些內容無法辨識（例如 |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

已在原始文件中偵測到問題，這使得若以原始格式儲存，文件很可能無法開啟。

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

載入後的文件樹或儲存後產生的文件中，文字/圖表/影像或其他資料將會完全缺失。

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

主要格式遺失。

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

輕微格式遺失。

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

這是一個已知問題，會阻止某些使用者代理或其舊版開啟文件。

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

原始文件中的某些內容無法辨識（例如不受支援），這可能會或可能不會導致問題或造成資料/格式遺失。