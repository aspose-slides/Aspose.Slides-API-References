---
title: Rectangle()
second_title: Aspose.Slides for C++ API リファレンス
description: X および Y 座標と幅と高さの値が 0 に設定された矩形を表す Rectangle オブジェクトの新しいインスタンスを構築します。
type: docs
weight: 1
url: /ja/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() コンストラクタ

X と Y の座標と幅と高さの値が 0 に設定された矩形を表す [Rectangle](../) オブジェクトの新しいインスタンスを作成します。

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) コンストラクタ

左上隅の指定された座標と幅と高さを持つ矩形を表す [Rectangle](../) オブジェクトの新しいインスタンスを作成します。

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | int | 矩形の左上隅の X 座標の値 |
| y | int | 矩形の左上隅の Y 座標の値 |
| width | int | 矩形の幅 |
| height | int | 矩形の高さ |

## Rectangle::Rectangle(const Point\&, const Size\&) コンストラクタ

[Rectangle](../) オブジェクトの新しいインスタンスを作成します。このオブジェクトは、左上隅の座標が [Point](../../point/) クラスのインスタンスとして指定され、幅と高さが [Size](../../size/) クラスのインスタンスとして指定された矩形を表します。

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| location | const [Point](../../point/)\& | 矩形の左上隅の位置を指定します |
| size | const [Size](../../size/)\& | 矩形の幅と高さを指定します |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) コンストラクタ

[Rectangle](../) オブジェクトの新しいインスタンスを作成します。このオブジェクトは、指定された矩形と等価な矩形を表します。

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | 構築されるオブジェクトが表す矩形の位置とサイズを指定する **System::Windows::Forms::Screen::Rectangle_** クラスのインスタンス |

## 参照

* クラス [Rectangle](../)
* クラス [Point](../../point/)
* クラス [Size](../../size/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)