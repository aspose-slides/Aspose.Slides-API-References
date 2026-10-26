---
title: Contains()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトで表される矩形内に、指定された点があるかどうかを判定します。
type: docs
weight: 248
url: /ja/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const メソッド

現在のオブジェクトで表される矩形内に、指定された点があるかどうかを判定します。

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | int | チェックする点の X 座標 |
| y | int | チェックする点の Y 座標 |

### 戻り値

指定された点が現在のオブジェクトで表される矩形内にある場合は True、そうでない場合は false を返します。

## Rectangle::Contains(const Point\&) const メソッド

現在のオブジェクトで表される矩形内に、指定された点があるかどうかを判定します。

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | チェックする点 |

### 戻り値

指定された点が現在のオブジェクトで表される矩形内にある場合は True、そうでない場合は false を返します。

## Rectangle::Contains(const Rectangle\&) const メソッド

現在のオブジェクトで表される矩形内に、指定された矩形があるかどうかを判定します。

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | チェックする矩形 |

### 戻り値

指定された矩形が現在のオブジェクトで表される矩形内にある場合は True、そうでない場合は false を返します。

## 参照

* クラス [Rectangle](../)
* クラス [Point](../../point/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)