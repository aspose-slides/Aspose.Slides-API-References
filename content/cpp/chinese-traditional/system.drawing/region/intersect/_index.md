---
title: Intersect()
second_title: Aspose.Slides for C++ API 參考文件
description: 將目前物件所表示的區域取代為此區域與由指定矩形定義之區域的交集結果。
type: docs
weight: 79
url: /zh-hant/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) 方法


將目前物件所表示的區域取代為此區域與由指定矩形定義之區域的交集結果。

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 定義要與此區域相交的矩形 |

## Region::Intersect(const Rectangle\&) 方法


將目前物件所表示的區域取代為此區域與由指定矩形定義之區域的交集結果。

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 定義要與此區域相交的矩形 |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 方法


將目前物件所表示的區域取代為此區域與由指定路徑定義之區域的交集結果。

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 定義要與此區域相交的路徑 |

## Region::Intersect(const SharedPtr\<Region\>\&) 方法


將目前物件所表示的區域取代為此區域與指定區域的交集結果。

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 定義要與此區域相交的區域 |

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [Region](../)
* 類別 [Rectangle](../../rectangle/)
* 類別 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)