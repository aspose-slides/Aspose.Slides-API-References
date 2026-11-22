---
title: set_range method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
設定圖表資料範圍。系列和類別將根據新的資料範圍進行更新。
如果資料範圍中的系列數量大於圖表資料中的系列計數，則會在集合末端新增與目前集合最後一個系列具有相同類型的附加系列。

```python
def set_range(self, formula):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| formula | **str** | 儲存格資料範圍公式。例如: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula 為 None。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 不支援的圖表類型 |
| **RuntimeError(Proxy error(ArgumentException))** | formula 格式不正確。 |

### 另請參閱
* 類別 [`ChartData`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)