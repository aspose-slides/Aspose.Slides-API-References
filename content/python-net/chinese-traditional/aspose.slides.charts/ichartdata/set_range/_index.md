---
title: set_range method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
設定圖表資料範圍。依據新資料範圍將會更新序列與類別。
如果資料範圍中的序列數量大於圖表資料中的序列計數，則會在目前集合的最後加入與最後一個序列相同類型的額外序列。

```python
def set_range(self, formula):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| formula | **str** | 單元格資料範圍公式。例如："Sheet1!$A$1:$C$4"、"SomeSheetName!A1:B100"、"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5"。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula 為 None。 |
| **RuntimeError(Proxy error(ArgumentException))** | formula 格式不正確。 |

### 另見
* 類別 [`IChartData`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)