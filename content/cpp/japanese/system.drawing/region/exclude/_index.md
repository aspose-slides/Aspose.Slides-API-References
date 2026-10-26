---
title: Exclude()
second_title: Aspose.Slides for C++ APIリファレンス
description: 現在のオブジェクトで表される領域を、指定された矩形で定義された領域を除外した結果の領域に置き換えます。
type: docs
weight: 92
url: /ja/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) メソッド

現在のオブジェクトで表される領域を、指定された矩形で定義された領域を除外した結果の領域に置き換えます。

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 除外する領域を定義する矩形 |

## Region::Exclude(const Rectangle\&) メソッド

現在のオブジェクトで表される領域を、指定された矩形で定義された領域を除外した結果の領域に置き換えます。

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 除外する領域を定義する矩形 |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) メソッド

現在のオブジェクトで表される領域を、指定されたパスで定義された領域を除外した結果の領域に置き換えます。

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 除外する領域を定義するパス |

## Region::Exclude(const SharedPtr\<Region\>\&) メソッド

現在のオブジェクトで表される領域を、指定された領域を除外した結果の領域に置き換えます。

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 除外する領域 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RectangleF](../../rectanglef/)
* クラス [Region](../)
* クラス [Rectangle](../../rectangle/)
* クラス [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)