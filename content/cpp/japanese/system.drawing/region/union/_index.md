---
title: Union()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す region を、この region と指定された rectangle で定義された region の union 操作の結果に置き換えます。
type: docs
weight: 53
url: /ja/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) メソッド

現在のオブジェクトが表す領域を、指定された矩形で定義された領域との合成結果に置き換えます。

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | この領域と合成する領域を定義する矩形 |

## Region::Union(const Rectangle\&) メソッド

現在のオブジェクトが表す領域を、指定された矩形で定義された領域との合成結果に置き換えます。

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | この領域と合成する領域を定義する矩形 |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) メソッド

現在のオブジェクトが表す領域を、指定されたパスで定義された領域との合成結果に置き換えます。

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | この領域と合成する領域を定義するパス |

## Region::Union(const SharedPtr\<Region\>\&) メソッド

現在のオブジェクトが表す領域を、この領域と指定された領域との合成結果に置き換えます。

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | この領域と合成する領域 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RectangleF](../../rectanglef/)
* クラス [Region](../)
* クラス [Rectangle](../../rectangle/)
* クラス [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)