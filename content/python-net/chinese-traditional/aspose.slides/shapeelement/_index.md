---
title: ShapeElement class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/shapeelement/
---
## ShapeElement 類別

表示具有相同輪廓和填充屬性的形狀的一部分。

ShapeElement 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/zh-hant/aspose.slides/shapeelement/parent_shape/) | 返回建立此元素的 Shape_PPT。<br/>            唯讀 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape). |
| [`path_points`](/slides/python-net/zh-hant/aspose.slides/shapeelement/path_points/) | 取得定義元素路徑幾何形狀的點陣列。 |
| [`path_types`](/slides/python-net/zh-hant/aspose.slides/shapeelement/path_types/) | 取得一個位元組值的陣列，用於指定元素路徑中每個點的類型。 <br/>            <br/>**0** 表示該點是圖形的起始點。<br/><br/><br/>**1** 表示該點是線段的兩個端點之一。<br/><br/><br/>**3** 表示該點是立方貝茲曲線的端點或控制點。<br/><br/><br/>**7** 掩蓋所有位元，僅保留最低三位，這三位表示點的類型。<br/><br/><br/>**16** 指定相應的線段為虛線。<br/><br/><br/>**32** 指定該點為標記點。<br/><br/><br/>**128** 指定該點是封閉子路徑（圖形）中的最後點。<br/><br/><br/>**129** 表示該資料點同時是線段端點且是封閉子路徑的最後點。 |
| [`fill_source`](/slides/python-net/zh-hant/aspose.slides/shapeelement/fill_source/) | 返回有關如何填充元素的資訊。<br/>            唯讀 [`ShapeElementFillSource`](/slides/python-net/zh-hant/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/zh-hant/aspose.slides/shapeelement/stroke_source/) | 返回有關如何描邊元素的資訊。<br/>            唯讀 [`ShapeElementStrokeSource`](/slides/python-net/zh-hant/aspose.slides/shapeelementstrokesource). |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)