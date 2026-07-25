---
title: Subtract()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された Size オブジェクトの幅と高さの値を、対応する指定された Point オブジェクトの X および Y 座標値からそれぞれ減算します。
type: docs
weight: 196
url: /ja/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) メソッド

指定された [Size](../../size/) オブジェクトの幅と高さの値を、対応する指定された [Point](../) オブジェクトの X および Y 座標の値からそれぞれ減算します。

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | const [Point](../)\& | 平行移動するポイント |
| size | const [Size](../../size/)\& | [Size](../../size/) オブジェクトは、**point** の座標値から減算する値を指定します |

### 戻り値

新しい [Point](../) オブジェクトで、X 座標の値は **point** の X 座標値から **size** の幅の値を減算した結果に等しく、Y 座標の値は **point** の Y 座標値から **size** の高さの値を減算した結果に等しい

## 参照

* クラス [Point](../)
* クラス [Size](../../size/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)