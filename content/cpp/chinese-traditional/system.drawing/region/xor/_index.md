---
title: Xor()
second_title: Aspose.Slides for C++ API 參考
description: 將目前物件所表示的區域，以此區域與由指定矩形所定義且不相交的部分取代。
type: docs
weight: 144
url: /zh-hant/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) 方法

將目前物件所表示的區域，以此區域與由指定矩形所定義且不相交的部分取代。

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 定義一個區域，與目前物件所表示的區域進行 xor 的矩形 |

## Region::Xor(const Rectangle\&) 方法

將目前物件所表示的區域，以此區域與由指定矩形所定義且不相交的部分取代。

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 定義一個區域，與目前物件所表示的區域進行 xor 的矩形 |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 方法

將目前物件所表示的區域，以此區域與由指定路徑所定義且不相交的部分取代。

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 定義一個區域，與目前物件所表示的區域進行 xor 的路徑 |

## Region::Xor(const SharedPtr\<Region\>\&) 方法

將目前物件所表示的區域，以此區域與指定區域中不相交的部分取代。

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 與目前物件所表示的區域進行 xor 的區域 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)