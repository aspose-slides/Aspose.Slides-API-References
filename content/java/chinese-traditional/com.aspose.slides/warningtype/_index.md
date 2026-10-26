---
title: WarningType
second_title: Aspose.Slides Java API 參考
description: 表示一種警告類型。
type: docs
url: /zh-hant/com.aspose.slides/warningtype/
---
**繼承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

表示一種類的警告。
## 欄位

| 欄位 | 描述 |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | 已偵測到來源文件中有問題，極可能導致文件若以原始格式儲存後無法開啟。 |
| [DataLoss](#DataLoss) | 文字/圖表/影像或其他資料在載入後的文件樹，或儲存後所產生的文件中將會完全缺失。 |
| [MajorFormattingLoss](#MajorFormattingLoss) | 重大格式遺失。 |
| [MinorFormattingLoss](#MinorFormattingLoss) | 輕微格式遺失。 |
| [CompatibilityIssue](#CompatibilityIssue) | 這是已知問題，會導致某些使用者代理或舊版使用者代理無法開啟文件。 |
| [UnexpectedContent](#UnexpectedContent) | 來源文件中的某些內容無法辨識（即 |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

已偵測到來源文件中有問題，極可能導致文件若以原始格式儲存後無法開啟。

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

文字/圖表/影像或其他資料在載入後的文件樹，或儲存後所產生的文件中將會完全缺失。

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

重大格式遺失。

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

輕微格式遺失。

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

這是已知問題，會導致某些使用者代理或舊版使用者代理無法開啟文件。

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

來源文件中的某些內容無法辨識（即不支援），這可能會造成問題，也可能不會，或導致資料/格式遺失。