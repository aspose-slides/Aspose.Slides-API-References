---
title: CompressionLevel
second_title: Aspose.Slides for C++ API 參考文件
description: 指定 OpenXML 檔案的 ZIP 壓縮等級。較高的等級可在較慢的處理速度下提供更好的壓縮效果。
type: docs
weight: 846
url: /zh-hant/aspose.slides.export/compressionlevel/
---
## CompressionLevel 列舉


指定 OpenXML 檔案的 ZIP 壓縮等級。較高的等級可在較慢的處理速度下提供更好的壓縮效果。

```cpp
enum class CompressionLevel
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| None | 0 | 未套用壓縮。檔案保持原樣儲存。 |
| Level1 | 1 | 最快的壓縮，且壓縮比率最低。 |
| Level2 | 2 | 較快的壓縮，且壓縮比率比 [CompressionLevel::Level1](./) 稍佳。 |
| Level3 | 3 | 提供比 [CompressionLevel::Level2](./) 更好的壓縮，且對效能的影響適中。 |
| Level4 | 4 | 提供比 [CompressionLevel::Level3](./) 更好的壓縮。 |
| Level5 | 5 | 提供比 [CompressionLevel::Level4](./) 改善的壓縮，並增加了處理時間。 |
| Level6 | 6 | 標準壓縮，於壓縮速度與檔案大小之間提供良好的平衡。預設的壓縮等級。 |
| Level7 | 7 | 提供比 [CompressionLevel::Level6](./) 更高的壓縮，但處理速度較慢。 |
| Level8 | 8 | 提供比 [CompressionLevel::Level7](./) 更高的壓縮。 |
| Level9 | 9 | 最大壓縮。產生最小的檔案大小，但處理速度最慢。 |

## 另請參閱

* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)