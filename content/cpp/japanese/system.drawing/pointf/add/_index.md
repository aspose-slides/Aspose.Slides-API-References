---
title: Add()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された SizeF オブジェクトの幅と高さの値を、指定された PointF オブジェクトの X および Y 座標値にそれぞれ加算します。
type: docs
weight: 144
url: /ja/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) メソッド

指定された[SizeF](../../sizef/)オブジェクトの幅と高さの値を、指定された[PointF](../)オブジェクトのXおよびY座標値にそれぞれ加算します。

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [PointF](../)\& | 変換対象の **point** |
| size | const [SizeF](../../sizef/)\& | 座標値に **point** の加算値を指定する [SizeF](../../sizef/) オブジェクト |

### 戻り値

新しい [PointF](../) オブジェクトで、X 座標値は **point** の X 座標値と **size** の幅の合計に等しく、Y 座標値は **point** の Y 座標値と **size** の高さの合計に等しいです。

## PointF::Add(const PointF\&, const Size\&) メソッド

指定された[Size](../../size/)オブジェクトの幅と高さの値を、指定された[PointF](../)オブジェクトのXおよびY座標値にそれぞれ加算します。

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [PointF](../)\& | 変換対象の **point** |
| size | const [Size](../../size/)\& | 座標値に **point** の加算値を指定する [Size](../../size/) オブジェクト |

### 戻り値

新しい [PointF](../) オブジェクトで、X 座標値は **point** の X 座標値と **size** の幅の合計に等しく、Y 座標値は **point** の Y 座標値と **size** の高さの合計に等しいです。

## 参照

* クラス [PointF](../)
* クラス [SizeF](../../sizef/)
* クラス [Size](../../size/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)