---
title: Sign()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 指定された符号付き整数値の符号を決定します。
type: docs
weight: 274
url: /ja/system/math/sign/
---
## Math::Sign(T) メソッド

指定された符号付き整数値の符号を決定します。

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 符号付き整数型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | T | 符号を判定する値 |

### 戻り値

- 1 は **value** が 0 未満の場合、0 は **value** が 0 と等しい場合、1 は **value** が 0 より大きい場合です。

## Math::Sign(T) メソッド

指定された浮動小数点値の符号を決定します。

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 引数の浮動小数点型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | T | 符号を判定する値 |

### 戻り値

- 1 は **value** が 0 未満の場合、0 は **value** が 0 と等しい場合、1 は **value** が 0 より大きい場合です。

## Math::Sign(const Decimal\&) メソッド

指定された十進数の値の符号を決定します。

```cpp
static int System::Math::Sign(const Decimal &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 符号を判定する値 |

### 戻り値

- 1 は **value** が 0 未満の場合、0 は **value** が 0 と等しい場合、1 は **value** が 0 より大きい場合です。

## 参照

* クラス [Decimal](../../decimal/)
* 構造体 [Math](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)