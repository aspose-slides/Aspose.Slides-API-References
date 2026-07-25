---
title: FillPolygon()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたブラシを使用して、指定されたポリゴンの内部を塗りつぶします。
type: docs
weight: 417
url: /ja/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) メソッド

指定されたブラシを使用して、指定されたポリゴンの内部を塗りつぶします。

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | [Brush](../../brush/) オブジェクトで、塗りつぶしのパラメータを指定します |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | ポリゴンを定義する点を含む配列 |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 塗りつぶしモード |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) メソッド

指定されたブラシを使用して、指定されたポリゴンの内部を塗りつぶします。

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | [Brush](../../brush/) オブジェクトで、塗りつぶしのパラメータを指定します |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | ポリゴンを定義する点を含む配列 |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 塗りつぶしモード |

## 参照

* 列挙型 [FillMode](../../../system.drawing.drawing2d/fillmode/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [Brush](../../brush/)
* クラス [Point](../../point/)
* クラス [Graphics](../)
* クラス [PointF](../../pointf/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)