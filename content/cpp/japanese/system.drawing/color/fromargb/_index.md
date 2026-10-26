---
title: FromArgb()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された色を表す Color クラスのインスタンスを作成します。
type: docs
weight: 235
url: /ja/system.drawing/color/fromargb/
---
## Color::FromArgb(int) メソッド

[Color](../) クラスのインスタンスを作成し、指定された色を表します。

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| argb | int | オブジェクトが表す色の 32 ビット ARGB 値 |

### 戻り値

指定された色を表すオブジェクト。

## Color::FromArgb(int, int, int, int) メソッド

[Color](../) クラスのインスタンスを作成し、指定された色を表します。

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alpha | int | 色のアルファ成分の値 |
| red | int | 色の赤成分の値 |
| green | int | 色の緑成分の値 |
| blue | int | 色の青成分の値 |

### 戻り値

指定された色を表すオブジェクト。

## Color::FromArgb(int, int, int) メソッド

[Color](../) クラスのインスタンスを作成し、アルファ成分が 0xFF に設定された指定された色を表します。

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| red | int | 色の赤成分の値 |
| green | int | 色の緑成分の値 |
| blue | int | 色の青成分の値 |

### 戻り値

指定された色を表すオブジェクト。

## Color::FromArgb(int, Color) メソッド

[Color](../) クラスのインスタンスを作成し、指定された色を表します。

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alpha | int | 色のアルファ成分の値 |
| base_color | [Color](../) | 作成されるオブジェクトが表す色の赤、緑、青成分を表す [Color](../) オブジェクトのインスタンス |

### 戻り値

指定された色を表すオブジェクト。

## 関連項目

* クラス [Color](../)
* 名前空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)