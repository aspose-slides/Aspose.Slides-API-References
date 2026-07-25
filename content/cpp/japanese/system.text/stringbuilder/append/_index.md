---
title: Append()
second_title: Aspose.Slides for C++ API リファレンス
description: ビルダーに文字を追加します。
type: docs
weight: 118
url: /ja/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) メソッド


文字をビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | 文字の値。 |

### 戻り値

このポインタ。

## StringBuilder::Append(char_t, int) メソッド


文字をビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | 文字の値。 |
| count | int | 挿入文字を繰り返す回数。 |

### 戻り値

このポインタ。

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) メソッド


文字配列をビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 追加する文字。 |

### 戻り値

このポインタ。

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) メソッド


文字配列のスライスをビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 追加する文字。 |
| startIndex | int | スライス開始インデックス。 |
| charCount | int | スライスの長さ。 |

### 戻り値

このポインタ。

## StringBuilder::Append(const String\&) メソッド


文字列をビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) を追加します。 |

### 戻り値

このポインタ。

## StringBuilder::Append(const String\&, int, int) メソッド


文字列のスライスをビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) を追加します。 |
| startIndex | int | スライス開始インデックス。 |
| charCount | int | スライスの長さ。 |

### 戻り値

このポインタ。

## StringBuilder::Append(const SharedPtr\<T\>\&) メソッド


オブジェクトの文字列表現をビルダーに追加します。

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) をシリアライズして追加します。 |

### 戻り値

このポインタ。

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) メソッド


ビルダーの内容をビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | 内容を追加するビルダー。 |

### 戻り値

このポインタ。

## StringBuilder::Append(float) メソッド


浮動小数点値をビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| f | **float** | シリアライズして追加する値。 |

### 戻り値

このポインタ。

## StringBuilder::Append(double) メソッド


浮動小数点値をビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| df | **double** | シリアライズして追加する値。 |

### 戻り値

このポインタ。

## StringBuilder::Append(int) メソッド


整数値をビルダーに追加します。

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| i | int | シリアライズして追加する値。 |

### 戻り値

このポインタ。

## StringBuilder::Append(T) メソッド


算術値をビルダーに追加します。

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 算術型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | T | シリアライズして追加する値。 |

### 戻り値

このポインタ。

## StringBuilder::Append(E) メソッド


列挙値の文字列表現をビルダーに追加します。

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| E | [Enum](../../../system/enum/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| e | E | シリアライズして追加する値。 |

### 戻り値

このポインタ。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)