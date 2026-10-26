---
title: Inflate()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す長方形の幅と高さを増加させ、長方形の幾何学的中心の位置を維持します。幅と高さは指定された量だけ両方向に増加します。
type: docs
weight: 261
url: /ja/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) メソッド

現在のオブジェクトが表す長方形の幅と高さを増加させ、長方形の幾何学的中心の位置を維持します。幅と高さは指定された量だけ両方向に増加します。

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | **float** | 長方形の width を両方向に増加させる量 |
| height | **float** | 長方形の height を両方向に増加させる量 |

## RectangleF::Inflate(const SizeF\&) メソッド

現在のオブジェクトが表す長方形の幅と高さを増加させ、長方形の幾何学的中心の位置を維持します。幅と高さは、指定されたサイズオブジェクトの width および height の値に対応して増加します。

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | [SizeF](../../sizef/) オブジェクトで、長方形の幅と高さを増加させる量を指定します |

## RectangleF::Inflate(const RectangleF\&, float, float) メソッド

指定されたオブジェクトが表す長方形の幅と高さを増加させ、長方形の幾何学的中心の位置を維持します。幅と高さは指定された量だけ両方向に増加します。

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 拡張する長方形 |
| x | **float** | 長方形の width を両方向に増加させる量 |
| y | **float** | 長方形の height を両方向に増加させる量 |

### 戻り値

[RectangleF](../) オブジェクトで、拡大された長方形を表します

## 参照

* クラス [RectangleF](../)
* クラス [SizeF](../../sizef/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)