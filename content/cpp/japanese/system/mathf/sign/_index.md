---
title: Sign()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された符号付き整数値の符号を決定します。
type: docs
weight: 274
url: /ja/system/mathf/sign/
---
## MathF::Sign(T) メソッド

指定された符号付き整数値の符号を決定します。

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | 整数の符号付き型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | 符号を判定する対象の値 |

### 戻り値

- 1 は **value** が 0 未満の場合; 0 は **value** が 0 と等しい場合; 1 は **value** が 0 より大きい場合

## MathF::Sign(T) メソッド

指定された浮動小数点値の符号を決定します。

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | 引数の浮動小数点型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | 符号を判定する対象の値 |

### 戻り値

- 1 は **value** が 0 未満の場合; 0 は **value** が 0 と等しい場合; 1 は **value** が 0 より大きい場合

## 参照

* 構造体 [MathF](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)