---
title: Intersect()
second_title: Aspose.Slides for C++ API 參考文件
description: 將目前物件所代表的矩形，以與指定物件所代表的矩形相交的結果矩形取代。
type: docs
weight: 274
url: /zh-hant/system.drawing/rectanglef/intersect/
---
## RectangleF::Intersect(const RectangleF\&) 方法

將目前物件所表示的矩形取代為與指定物件所表示的矩形相交後的矩形。

```cpp
void System::Drawing::RectangleF::Intersect(const RectangleF &rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 表示欲與目前物件所表示的矩形相交之矩形的 [RectangleF](../) 物件 |

## RectangleF::Intersect(const RectangleF\&, const RectangleF\&) 方法

傳回由指定矩形相交所得到的矩形。

```cpp
static RectangleF System::Drawing::RectangleF::Intersect(const RectangleF &a, const RectangleF &b)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const [RectangleF](../)\& | 第一個要相交的矩形 |
| b | const [RectangleF](../)\& | 第二個要相交的矩形 |

### 傳回值

**a** 與 **b** 交叉的結果

## 另請參閱

* 類別 [RectangleF](../)
* 命名空間 [System::Drawing](../../)
* 程式庫 [Aspose.Slides](../../../)