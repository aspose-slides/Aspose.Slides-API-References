---
title: Xor()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す region を、この region と指定された recangle で定義された region のうち、交差しない部分に置き換えます。
type: docs
weight: 144
url: /ja/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) メソッド

現在のオブジェクトが表す領域を、この領域と指定された長方形で定義された領域のうち、交差しない部分に置き換えます。

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 現在のオブジェクトが表す領域とxorする領域を定義する長方形 |

## Region::Xor(const Rectangle\&) メソッド

現在のオブジェクトが表す領域を、この領域と指定された長方形で定義された領域のうち、交差しない部分に置き換えます。

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 現在のオブジェクトが表す領域とxorする領域を定義する長方形 |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) メソッド

現在のオブジェクトが表す領域を、この領域と指定されたパスで定義された領域のうち、交差しない部分に置き換えます。

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 現在のオブジェクトが表す領域とxorする領域を定義するパス |

## Region::Xor(const SharedPtr\<Region\>\&) メソッド

現在のオブジェクトが表す領域を、この領域と指定された領域のうち、交差しない部分に置き換えます。

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 現在のオブジェクトが表す領域とxorする領域 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)