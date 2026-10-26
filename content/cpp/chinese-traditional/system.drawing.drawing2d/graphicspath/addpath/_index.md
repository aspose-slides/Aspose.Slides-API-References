---
title: AddPath()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的路徑添加到目前物件所代表的路徑中。
type: docs
weight: 222
url: /zh-hant/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) 方法

將指定的路徑添加到目前物件所代表的路徑中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | 要添加的路徑 |
| connect | **bool** | True 表示 **path** 中的最後第一個圖形是目前物件所代表路徑的最後圖形的一部分；false 表示 **path** 中的第一個圖形與目前物件所代表路徑的最後圖形是分離的圖形 |

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [GraphicsPath](../)
* 命名空間 [System::Drawing::Drawing2D](../../)
* 函式庫 [Aspose.Slides](../../../)