---
title: Complement()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトで表される領域を、指定された矩形で定義された領域のうち、この領域と交差しない部分に置き換えます。
type: docs
weight: 131
url: /ja/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) メソッド

現在のオブジェクトで表される領域を、指定された矩形で定義され、かつこの領域と交差しない部分で置き換えます。

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 補完対象の領域を定義する矩形 |

## Region::Complement(const Rectangle\&) メソッド

現在のオブジェクトで表される領域を、指定された矩形で定義され、かつこの領域と交差しない部分で置き換えます。

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 補完対象の領域を定義する矩形 |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) メソッド

現在のオブジェクトで表される領域を、指定されたパスで定義され、かつこの領域と交差しない部分で置き換えます。

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 補完対象の領域を定義するパス |

## Region::Complement(const SharedPtr\<Region\>\&) メソッド

現在のオブジェクトで表される領域を、指定された領域で定義され、かつこの領域と交差しない部分で置き換えます。

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 補完対象の領域 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RectangleF](../../rectanglef/)
* クラス [Region](../)
* クラス [Rectangle](../../rectangle/)
* クラス [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)