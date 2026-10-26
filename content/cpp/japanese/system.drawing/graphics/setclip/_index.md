---
title: SetClip()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の Graphics オブジェクトで表される描画サーフェスのクリッピング領域を、現在のクリップ領域と指定された領域を結合する指定された操作の結果に設定します。
type: docs
weight: 690
url: /ja/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) メソッド

[Graphics](../) オブジェクトで表される描画サーフェスのクリッピング領域を、現在のクリップ領域と指定された領域を結合する指定された操作の結果に設定します。

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | 結合する領域を指定します |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 結合操作を指定します |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) メソッド

[Graphics](../) オブジェクトで表される描画サーフェスのクリッピング領域を、現在のクリップ領域と指定された領域を結合する指定された操作の結果に設定します。

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | 結合する領域を指定します |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 結合操作を指定します |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) メソッド

[Graphics](../) オブジェクトで表される描画サーフェスのクリッピング領域を、現在のクリップ領域と指定された領域を結合する指定された操作の結果に設定します。

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | 結合する領域を指定します |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 結合操作を指定します |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) メソッド

実装されていません。

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) メソッド

[Graphics](../) オブジェクトで表される描画サーフェスのクリッピング領域を、現在のクリップ領域とグラフィックパスで指定された領域を結合する指定された操作の結果に設定します。

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 結合する領域を指定します |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 結合操作を指定します |

## 参照

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)