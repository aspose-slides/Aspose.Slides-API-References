---
title: Equals()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 14
url: /ja/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) メソッド




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) メソッド


C# の [Object.Equals](../../object/equals/) 呼び出しの代替で、C++ で任意の型に対して機能します。スマート ポインタ型のオーバーロードです。

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 最初のオブジェクト型。 |
| T2 | 2 番目のオブジェクト型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | 最初のオブジェクト。 |
| another | const T2\& | 2 番目のオブジェクト。 |

### 戻り値

オブジェクトが等しいとみなされる場合は True、そうでない場合は False。

## ObjectExt::Equals(T, const T2\&) メソッド


C# の [Object.Equals](../../object/equals/) 呼び出しの代替で、C++ で任意の型に対して機能します。構造体型のオーバーロードです。

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 最初のオブジェクト型。 |
| T2 | 2 番目のオブジェクト型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | T | 最初のオブジェクト。 |
| another | const T2\& | 2 番目のオブジェクト。 |

### 戻り値

オブジェクトが等しいとみなされる場合は True、そうでない場合は False。

## ObjectExt::Equals(const T\&, const T2\&) メソッド


C# の [Object.Equals](../../object/equals/) 呼び出しの代替で、C++ で任意の型に対して機能します。スカラー型のオーバーロードです。

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 最初のオブジェクト型。 |
| T2 | 2 番目のオブジェクト型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | 最初のオブジェクト。 |
| another | const T2\& | 2 番目のオブジェクト。 |

### 戻り値

オブジェクトが等しいとみなされる場合は True、そうでない場合は False。

## ObjectExt::Equals(const char_t(&), String) メソッド


C# の [Object.Equals](../../object/equals/) 呼び出しの代替で、C++ で任意の型に対して機能します。文字列リテラルと文字列の比較用オーバーロードです。

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| N | [String](../../string/) リテラル サイズ。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) リテラル。 |
| another | [String](../../string/) | [String](../../string/)。 |

### 戻り値

オブジェクトが等しいとみなされる場合は True、そうでない場合は False。

## ObjectExt::Equals(const float\&, const float\&) メソッド


C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは NaN 同士を等しいとみなします。

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const **float**\& | LHS 浮動小数点値。 |
| another | const **float**\& | RHS 浮動小数点値。 |

### 戻り値

**obj** と **another** の両方が NaN であるか、等しい場合は True、そうでない場合は False。

## ObjectExt::Equals(const double\&, const double\&) メソッド


C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは NaN 同士を等しいとみなします。

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const **double**\& | LHS 浮動小数点値。 |
| another | const **double**\& | RHS 浮動小数点値。 |

### 戻り値

**obj** と **another** の両方が NaN であるか、等しい場合は True、そうでない場合は False。

## 関連項目

* クラス [ObjectExt](../)
* クラス [String](../../string/)
* 構造体 [IsExceptionWrapper](../../isexceptionwrapper/)
* 構造体 [IsSmartPtr](../../issmartptr/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)