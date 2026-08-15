---
title: get_PathTypes()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得一個位元組陣列，以指定元素路徑中每個點的類型。
type: docs
weight: 27
url: /zh-hant/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() 方法


取得一個位元組陣列，以指定元素路徑中每個點的類型。

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## 備註


**0** 表示該點是圖形的起點。

**1** 表示該點是線段的兩個端點之一。

**3** 表示該點是立方貝塞爾樣條的端點或控制點。

**7** 掩蔽除最低三位元外的所有位元，這三位元指示點的類型。

**16** 指定相應的線段為虛線。

**32** 指定該點為標記。

**128** 指定該點是封閉子路徑（圖形）中的最後一個點。

**129** 表示此資料點同時是線段的端點且是封閉子路徑的最後一個點。

## 另見

* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ShapeElement](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)