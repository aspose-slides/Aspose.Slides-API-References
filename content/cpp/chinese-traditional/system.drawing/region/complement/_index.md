---
title: Complement()
second_title: Aspose.Slides for C++ API 參考
description: 將目前物件所代表的區域取代為由指定矩形定義且不與此區域相交的區域部分。
type: docs
weight: 131
url: /zh-hant/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) 方法

將目前物件所代表的區域取代為由指定矩形定義且不與此區域相交的區域部分。

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 定義要補集之區域的矩形 |

## Region::Complement(const Rectangle\&) 方法

將目前物件所代表的區域取代為由指定矩形定義且不與此區域相交的區域部分。

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 定義要補集之區域的矩形 |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 方法


將目前物件所代表的區域取代為由指定路徑定義且不與此區域相交的區域部分。

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 定義要補集之區域的路徑 |

## Region::Complement(const SharedPtr\<Region\>\&) 方法


將目前物件所代表的區域取代為由指定區域定義且不與此區域相交的區域部分。

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 要補集的區域 |

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [Region](../)
* 類別 [Rectangle](../../rectangle/)
* 類別 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)