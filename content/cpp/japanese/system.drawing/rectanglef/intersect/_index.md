---
title: Intersect()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す矩形を、指定されたオブジェクトが表す矩形との交差結果となる矩形に置き換えます。
type: docs
weight: 274
url: /ja/system.drawing/rectanglef/intersect/
---
## RectangleF::Intersect(const RectangleF\&) メソッド


現在のオブジェクトが表す矩形を、指定されたオブジェクトが表す矩形との交差結果となる矩形に置き換えます。

```cpp
void System::Drawing::RectangleF::Intersect(const RectangleF &rect)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | [RectangleF](../) オブジェクトは、現在のオブジェクトが表す矩形と交差させる矩形を表します |

## RectangleF::Intersect(const RectangleF\&, const RectangleF\&) メソッド


指定された矩形の交差結果となる矩形を返します。

```cpp
static RectangleF System::Drawing::RectangleF::Intersect(const RectangleF &a, const RectangleF &b)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const [RectangleF](../)\& | 交差させる最初の矩形 |
| b | const [RectangleF](../)\& | 交差させる 2 番目の矩形 |

### 戻り値

**a** と **b** の交差の結果

## 参照

* クラス [RectangleF](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)