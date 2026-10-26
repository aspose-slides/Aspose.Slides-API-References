---
title: Inflate()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトで表される矩形の幅と高さを増加させ、矩形の幾何学的中心の位置を維持します。幅と高さは指定された量だけ両方向に増加します。
type: docs
weight: 261
url: /ja/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) メソッド

現在のオブジェクトで表される矩形の幅と高さを増加させ、矩形の幾何学的中心の位置を維持します。幅と高さは指定された量だけ両方向に増加します。

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | int | 矩形の幅が両方向に増加する量 |
| height | int | 矩形の高さが両方向に増加する量 |

## Rectangle::Inflate(const Size\&) メソッド

現在のオブジェクトで表される矩形の幅と高さを増加させ、矩形の幾何学的中心の位置を維持します。幅と高さは、指定されたサイズオブジェクトの幅と高さの値に対応して増加します。

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| size | const [Size](../../size/)\& | [Size](../../size/)オブジェクトは、矩形の幅と高さを増加させる量を指定します |

## Rectangle::Inflate(const Rectangle\&, int, int) メソッド

指定されたオブジェクトで表される矩形の幅と高さを増加させ、矩形の幾何学的中心の位置を維持します。幅と高さは指定された量だけ両方向に増加します。

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 拡張対象の矩形 |
| x | int | 矩形の幅が両方向に増加する量 |
| y | int | 矩形の高さが両方向に増加する量 |

### 戻り値

拡大された矩形を表す[Rectangle](../)オブジェクト

## 参照

* クラス [Rectangle](../)
* クラス [Size](../../size/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)