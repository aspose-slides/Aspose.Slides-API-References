---
title: PieSplitType
second_title: Aspose.Slides for C++ API 參考文件
description: 表示在 pie-of-pie 或 bar-of-pie 圖表中第二個圓餅或條形圖的分割點類型。
type: docs
weight: 1665
url: /zh-hant/aspose.slides.charts/piesplittype/
---
## PieSplitType 列舉


表示在圓餅圖中圓餅或條形圖的第二層（pie-of-pie 或 bar-of-pie 圖表）之分割點類型。

```cpp
enum class PieSplitType
```

### Values

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Default | 0 | 指定資料點應使用此圖表類型的預設機制進行分割。 |
| Custom | 1 | 指定資料點應依據 Custom Split 值在圓餅圖與第二圖表之間分割。 |
| ByPercentage | 2 | 指定資料點應透過將百分比低於 Split Position 百分比的點放入第二圖表，來在圓餅圖與第二圖表之間分割。 |
| ByPos | 3 | 指定資料點應透過將資料點的最後 Split Position 放入第二圖表，來在圓餅圖與第二圖表之間分割。 |
| ByValue | 4 | 指定資料點應透過將值低於 Split Position 的資料點放入第二圖表，來在圓餅圖與第二圖表之間分割。 |

## 另請參閱

* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)