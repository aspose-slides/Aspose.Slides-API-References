---
title: Exclude()
second_title: Aspose.Slides for C++ API 參考文件
description: 將當前物件所表示的區域取代為從中排除指定矩形所定義的區域的結果。
type: docs
weight: 92
url: /zh-hant/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) method


將當前物件所表示的區域取代為從中排除指定 rectange 定義的區域的結果。

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 定義要排除之區域的矩形 |

## Region::Exclude(const Rectangle\&) method


將當前物件所表示的區域取代為從中排除指定 rectange 定義的區域的結果。

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 定義要排除之區域的矩形 |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) method


將當前物件所表示的區域取代為從中排除指定路徑定義的區域的結果。

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 定義要排除之區域的路徑 |

## Region::Exclude(const SharedPtr\<Region\>\&) method


將當前物件所表示的區域取代為從中排除指定區域的結果。

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 要排除的區域 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [Region](../)
* 類別 [Rectangle](../../rectangle/)
* 類別 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)