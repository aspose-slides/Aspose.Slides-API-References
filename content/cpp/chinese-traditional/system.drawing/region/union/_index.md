---
title: Union()
second_title: Aspose.Slides for C++ API 參考文件
description: 將當前物件所代表的區域取代為此區域與由指定矩形定義之區域的聯集運算結果。
type: docs
weight: 53
url: /zh-hant/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) 方法


將當前物件所代表的區域取代為此區域與由指定矩形定義之區域的聯集運算結果。

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 一個矩形，定義要與此區域合併的區域 |

## Region::Union(const Rectangle\&) 方法


將當前物件所代表的區域取代為此區域與由指定矩形定義之區域的聯集結果。

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 一個矩形，定義要與此區域合併的區域 |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 方法


將當前物件所代表的區域取代為此區域與由指定路徑定義之區域的聯集結果。

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 一條路徑，定義要與此區域合併的區域 |

## Region::Union(const SharedPtr\<Region\>\&) 方法


將當前物件所代表的區域取代為此區域與指定區域的聯集結果。

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 一個區域，用於與此區域合併 |

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [Region](../)
* 類別 [Rectangle](../../rectangle/)
* 類別 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)