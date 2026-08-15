---
title: GraphicsPath()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個使用指定填充模式的 GraphicsPath 類別的新實例。
type: docs
weight: 1
url: /zh-hant/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) 建構函式


建立一個使用指定填充模式的 [GraphicsPath](../) 類別的新實例。

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | 指定被建立之物件所表示的封閉路徑的內部應如何填充 |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) 建構函式


建立一個代表指定路徑的 [GraphicsPath](../) 物件的新實例。

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 包含用於指定將由被建立之物件表示的路徑之點的陣列 |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含指定 **pts** 陣列中相應點類型之值的陣列 |
| fillMode | [FillMode](../../fillmode/) | 指定被建立之物件所表示的封閉路徑的內部應如何填充 |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) 建構函式


建立一個代表指定路徑的 [GraphicsPath](../) 物件的新實例。

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 包含用於指定將由被建立之物件表示的路徑之點的陣列 |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含指定 **pts** 陣列中相應點類型之值的陣列 |
| fillMode | [FillMode](../../fillmode/) | 指定被建立之物件所表示的封閉路徑的內部應如何填充 |

## GraphicsPath::GraphicsPath(const SkPath\&) 建構函式




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## 另請參閱

* 列舉 [FillMode](../../fillmode/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [GraphicsPath](../)
* 類別 [Point](../../../system.drawing/point/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 命名空間 [System::Drawing::Drawing2D](../../)
* 程式庫 [Aspose.Slides](../../../)