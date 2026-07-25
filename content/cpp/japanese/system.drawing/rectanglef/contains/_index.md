---
title: Contains()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された点が現在のオブジェクトで表される矩形内にあるかどうかを判定します。
type: docs
weight: 248
url: /ja/system.drawing/rectanglef/contains/
---
## RectangleF::Contains(float, float) method

指定された点が現在のオブジェクトで表される矩形内にあるかどうかを判断します。

```cpp
bool System::Drawing::RectangleF::Contains(float x, float y)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 確認する点の X 座標 |
| y | **float** | 確認する点の Y 座標 |

### 戻り値

指定された点が現在のオブジェクトで表される矩形内にある場合は True、そうでない場合は false

## RectangleF::Contains(const PointF\&) method

指定された点が現在のオブジェクトで表される矩形内にあるかどうかを判断します。

```cpp
bool System::Drawing::RectangleF::Contains(const PointF &point)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 確認する点 |

### 戻り値

指定された点が現在のオブジェクトで表される矩形内にある場合は True、そうでない場合は false

## RectangleF::Contains(const RectangleF\&) method

指定された矩形が現在のオブジェクトで表される矩形内にあるかどうかを判断します。

```cpp
bool System::Drawing::RectangleF::Contains(const RectangleF &rect)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 確認する矩形 |

### 戻り値

指定された矩形が現在のオブジェクトで表される矩形内にある場合は True、そうでない場合は false

## 参照

* クラス [RectangleF](../)
* クラス [PointF](../../pointf/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)