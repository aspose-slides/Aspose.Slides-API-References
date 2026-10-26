---
title: FillPolygon()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的畫筆填充指定多邊形的內部。
type: docs
weight: 417
url: /zh-hant/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) 方法

使用指定的畫筆填充指定多邊形的內部。

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 一個 [Brush](../../brush/) 物件，指定填充的參數 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 包含定義多邊形之點的陣列 |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 填充模式 |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) 方法

使用指定的畫筆填充指定多邊形的內部。

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 一個 [Brush](../../brush/) 物件，指定填充的參數 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | 包含定義多邊形之點的陣列 |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 填充模式 |

## 另請參閱

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)