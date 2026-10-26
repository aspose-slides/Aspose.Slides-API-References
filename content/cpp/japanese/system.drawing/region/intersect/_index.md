---
title: Intersect()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す領域を、指定された矩形で定義された領域との交差結果に置き換えます。
type: docs
weight: 79
url: /ja/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) メソッド

現在のオブジェクトが表す領域を、指定された矩形で定義された領域との交差結果に置き換えます。

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | この領域と交差させる領域を定義する矩形 |

## Region::Intersect(const Rectangle\&) メソッド

現在のオブジェクトが表す領域を、指定された矩形で定義された領域との交差結果に置き換えます。

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | この領域と交差させる領域を定義する矩形 |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) メソッド

現在のオブジェクトが表す領域を、指定されたパスで定義された領域との交差結果に置き換えます。

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | この領域と交差させる領域を定義するパス |

## Region::Intersect(const SharedPtr\<Region\>\&) メソッド

現在のオブジェクトが表す領域を、指定された領域との交差結果に置き換えます。

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | この領域と交差させる領域 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RectangleF](../../rectanglef/)
* クラス [Region](../)
* クラス [Rectangle](../../rectangle/)
* クラス [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)