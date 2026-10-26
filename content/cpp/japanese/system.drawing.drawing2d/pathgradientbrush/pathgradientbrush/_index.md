---
title: PathGradientBrush()
second_title: Aspose.Slides for C++ API リファレンス
description: PathGradientBrush クラスの新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.drawing.drawing2d/pathgradientbrush/pathgradientbrush/
---
## PathGradientBrush::PathGradientBrush(const ArrayPtr\<PointF\>\&, WrapMode) constructor

[PathGradientBrush](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<PointF> &points, WrapMode wrapMode=WrapMode::Clamp)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | パスの頂点を含む配列 |
| wrapMode | [WrapMode](../../wrapmode/) | 創造されたオブジェクトで表されるブラシで描画された塗りがどのようにタイル状になるかを指定します |

## PathGradientBrush::PathGradientBrush(const ArrayPtr\<Point\>\&, WrapMode) constructor

[PathGradientBrush](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<Point> &points, WrapMode wrapMode=WrapMode::Clamp)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | パスの頂点を含む配列 |
| wrapMode | [WrapMode](../../wrapmode/) | 創造されたオブジェクトで表されるブラシで描画された塗りがどのようにタイル状になるかを指定します |

## PathGradientBrush::PathGradientBrush(const SharedPtr\<GraphicsPath\>\&) constructor

[PathGradientBrush](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const SharedPtr<GraphicsPath> &path)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 作成されたオブジェクトで塗りつぶされるパスを指定する [GraphicsPath](../../graphicspath/) オブジェクト |

## 参照

* 列挙型 [WrapMode](../../wrapmode/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [PathGradientBrush](../)
* クラス [Point](../../../system.drawing/point/)
* クラス [GraphicsPath](../../graphicspath/)
* 名前空間 [System::Drawing::Drawing2D](../../)
* ライブラリ [Aspose.Slides](../../../)