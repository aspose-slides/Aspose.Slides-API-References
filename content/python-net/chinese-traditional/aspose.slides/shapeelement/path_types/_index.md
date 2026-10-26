---
title: path_types property
second_title: Aspose.Slides for Python via .NET API 參考
description:
type: docs
url: /zh-hant/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types 屬性
取得一個位元組值的陣列，用於指定元素路徑中每個點的類型。

**0** 表示該點是圖形的起點。

**1** 表示該點是線段的兩個端點之一。

**3** 表示該點是三次貝茲曲線樣條的端點或控制點。

**7** 掩蔽除最低三位以外的所有位元，這三位指示點的類型。

**16** 指定相應的線段為虛線。

**32** 指定該點為標記。

**128** 指定該點是封閉子路徑（圖形）中的最後一個點。

**129** 表示該資料點同時是線段的端點且是封閉子路徑的最後一個點。

### 定義：
```python
@property
def path_types(self):
    ...
```

### 另見
* 類別 [`ShapeElement`](/slides/python-net/zh-hant/aspose.slides/shapeelement)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)