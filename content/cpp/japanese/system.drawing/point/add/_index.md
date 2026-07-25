---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された Size オブジェクトの幅と高さの値を、指定された Point オブジェクトの X および Y 座標値にそれぞれ加算します。
type: docs
weight: 183
url: /ja/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) メソッド

指定された [Size](../../size/) オブジェクトの幅と高さの値を、指定された [Point](../) オブジェクトの X および Y 座標値にそれぞれ加算します。

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [Point](../)\& | point を変換する |
| size | const [Size](../../size/)\& | [Size](../../size/) オブジェクトで、**point** の座標値に加算する値を指定します。 |

### 戻り値

新しい [Point](../) オブジェクトで、X 座標値は **point** の X 座標値と **size** の幅の合計に等しく、Y 座標値は **point** の Y 座標値と **size** の高さの合計に等しい。

## 関連項目

* クラス [Point](../)
* クラス [Size](../../size/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)