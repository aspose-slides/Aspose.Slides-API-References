---
title: operator+()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列連結演算子。
type: docs
weight: 274
url: /ja/system/string/operator_plus/
---
## String::operator+(const String\&) const method


[String](../) 連結演算子。

```cpp
String System::String::operator+(const String &str) const
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 現在の文字列の末尾に追加するための。 |

### 戻り値

連結された文字列。

## String::operator+(const T\&) const method


[String](../) 文字列リテラルまたは文字列ポインタとの連結。

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | 文字列リテラルまたは文字列ポインタ形式のいずれか。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg | const T\& | 現在の文字列と連結する対象。 |

### 戻り値

連結された文字列。

## String::operator+(char_t) const method


文字列の末尾に文字を追加します。

```cpp
String System::String::operator+(char_t x) const
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | char_t | 追加する文字。 |

### 戻り値

[String](../) 連結結果。

## String::operator+(int) const method


整数値の文字列表現を文字列の末尾に追加します。

```cpp
String System::String::operator+(int i) const
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| i | int | 文字列に変換して追加する整数値。 |

### 戻り値

[String](../) 連結結果。

## String::operator+(uint32_t) const method


符号なし整数値の文字列表現を文字列の末尾に追加します。

```cpp
String System::String::operator+(uint32_t i) const
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| i | **uint32_t** | 文字列に変換して追加する値。 |

### 戻り値

[String](../) 連結結果。

## String::operator+(double) const method


浮動小数点値の文字列表現を文字列の末尾に追加します。

```cpp
String System::String::operator+(double d) const
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| d | **double** | 文字列に変換して追加する値。 |

### 戻り値

[String](../) 連結結果。

## String::operator+(int64_t) const method


整数値の文字列表現を文字列の末尾に追加します。

```cpp
String System::String::operator+(int64_t v) const
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| v | **int64_t** | 文字列に変換して追加する値。 |

### 戻り値

[String](../) 連結結果。

## String::operator+(const T\&) const method


参照型オブジェクトの文字列表現を文字列の末尾に追加します。

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | ポインタ型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) を [ToString()](../tostring/) 呼び出しで文字列に変換し、現在の文字列に追加する。 |

### 戻り値

[String](../) 連結結果。

## String::operator+(const T\&) const method


値型オブジェクトの文字列表現を文字列の末尾に追加します。

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [ToString()](../tostring/) を呼び出す値型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) を [ToString()](../tostring/) 呼び出しで文字列に変換し、現在の文字列に追加する。 |

### 戻り値

[String](../) 連結結果。

## String::operator+(T) const method


ブール値の文字列表現を文字列の末尾に追加します。

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | 文字列と連結する値型。bool である必要があります。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) の値を文字列に変換し、追加する。 |

### 戻り値

[String](../) 連結結果。

## 参照

* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)