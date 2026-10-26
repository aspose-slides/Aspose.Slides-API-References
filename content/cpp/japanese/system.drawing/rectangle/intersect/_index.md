---
title: Intersect()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す矩形を、指定されたオブジェクトが表す矩形との交差結果として得られる矩形に置き換えます。
type: docs
weight: 274
url: /ja/system.drawing/rectangle/intersect/
---
## Rectangle::Intersect(const Rectangle\&) メソッド

現在のオブジェクトが表す矩形を、指定されたオブジェクトが表す矩形との交差結果の矩形に置き換えます。

```cpp
void System::Drawing::Rectangle::Intersect(const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 現在のオブジェクトが表す矩形と交差させる矩形を表す [Rectangle](../) オブジェクト |

## Rectangle::Intersect(const Rectangle\&, const Rectangle\&) メソッド

指定された矩形の交差結果となる矩形を返します。

```cpp
static Rectangle System::Drawing::Rectangle::Intersect(const Rectangle &a, const Rectangle &b)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const [Rectangle](../)\& | 交差させる最初の矩形 |
| b | const [Rectangle](../)\& | 交差させる2番目の矩形 |

### 戻り値

**a** と **b** の交差結果

## 参照

* クラス [Rectangle](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)