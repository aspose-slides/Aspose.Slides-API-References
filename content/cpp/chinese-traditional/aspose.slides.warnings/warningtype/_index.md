---
title: WarningType
second_title: Aspose.Slides for C++ API 參考
description: 代表一種警告類型。
type: docs
weight: 92
url: /zh-hant/aspose.slides.warnings/warningtype/
---
## WarningType 列舉

代表一種警告類型。

```cpp
enum class WarningType
```

### Values

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| SourceFileCorruption | 0 | 已偵測到來源文件中有問題，若以原始格式儲存，文件很可能無法開啟。 |
| DataLoss | 1 | 文字、圖表、影像或其他資料在載入後的文件樹，或儲存後產生的文件中將全部遺失。 |
| MajorFormattingLoss | 2 | 重大格式遺失。 |
| MinorFormattingLoss | 3 | 輕微格式遺失。 |
| CompatibilityIssue | 4 | 已知此問題會導致某些使用者代理程式或舊版使用者代理程式無法開啟文件。 |
| UnexpectedContent | 99 | 來源文件中的某些內容無法被識別（即不受支援），這可能會導致問題或造成資料/格式遺失，也可能不會。 |

## 另請參閱

* 命名空間 [Aspose::Slides::Warnings](../)
* 函式庫 [Aspose.Slides](../../)