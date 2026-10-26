---
title: Point()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい Point オブジェクトを作成し、その X および Y 座標の値を 0 に初期化します。
type: docs
weight: 1
url: /ja/system.drawing/point/point/
---
## Point::Point() コンストラクタ

新しい [Point](../) オブジェクトを作成し、その X および Y 座標の値を 0 に初期化します。

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) コンストラクタ

指定された値で新しい [Point](../) オブジェクトを作成し、初期化します。

```cpp
System::Drawing::Point::Point(int x, int y)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | int | X 座標の値 |
| y | int | Y 座標の値 |

## Point::Point(const Size\&) コンストラクタ

新しい [Point](../) オブジェクトを作成し、対応する [SizeF](../../sizef/) オブジェクトの幅と高さの値でそれぞれ X および Y 座標の値を初期化します。

```cpp
System::Drawing::Point::Point(const Size &size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| size | const [Size](../../size/)\& | 作成中の [Point](../) オブジェクトの X および Y 座標の値を初期化するために幅と高さの値が使用される [SizeF](../../sizef/) オブジェクト |

## Point::Point(int) コンストラクタ

指定された 32 ビット整数の上位 16 ビットで形成された値で X 座標の値を、下位 16 ビットで形成された値で Y 座標の値を初期化して新しい [Point](../) オブジェクトを作成します。

```cpp
System::Drawing::Point::Point(int dw)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dw | int | 作成されるオブジェクトの X 座標の値を上位 16 ビットで、Y 座標の値を下位 16 ビットで指定する 32 ビット整数値 |

## 参照

* クラス [Point](../)
* クラス [Size](../../size/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)