---
title: Subtract()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された SizeF オブジェクトの幅と高さの値を、指定された PointF オブジェクトの X および Y 座標の値からそれぞれ減算します。
type: docs
weight: 157
url: /ja/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) メソッド


指定された[SizeF](../../sizef/)オブジェクトの幅と高さの値を、指定された[PointF](../)オブジェクトのXおよびY座標の値からそれぞれ減算します。

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [PointF](../)\& | 変換する点 |
| size | const [SizeF](../../sizef/)\& | **point**の座標値から減算する値を指定する[SizeF](../../sizef/)オブジェクト |

### 戻り値

**point**のX座標から**size**の幅の値を減算し、Y座標から**size**の高さの値を減算した結果となる新しい[PointF](../)オブジェクト

## PointF::Subtract(const PointF\&, const Size\&) メソッド


指定された[Size](../../size/)オブジェクトの幅と高さの値を、指定された[PointF](../)オブジェクトのXおよびY座標の値からそれぞれ減算します。

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [PointF](../)\& | 変換する点 |
| size | const [Size](../../size/)\& | **point**の座標値から減算する値を指定する[Size](../../size/)オブジェクト |

### 戻り値

**point**のX座標から**size**の幅の値を減算し、Y座標から**size**の高さの値を減算した結果となる新しい[PointF](../)オブジェクト

## 参照

* クラス [PointF](../)
* クラス [SizeF](../../sizef/)
* クラス [Size](../../size/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)