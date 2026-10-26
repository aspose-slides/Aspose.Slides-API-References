---
title: ToString()
second_title: Aspose.Slides for C++ API リファレンス
description: 任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。
type: docs
weight: 27
url: /ja/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) リテラルを文字列に変換します。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## ObjectExt::ToString(const Nullable\<T\>\&) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Nullable](../../nullable/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) オブジェクトを文字列に変換します。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## ObjectExt::ToString(const T\&) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Enum](../../enum/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) 値を文字列に変換します。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## ObjectExt::ToString(const T\&) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スマートポインタ型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) 値を文字列に変換します。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## ObjectExt::ToString(T\&) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スマートポインタ型または [ExceptionWrapper](../../exceptionwrapper/)。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | T\& | 文字列に変換するスマートポインタまたは [ExceptionWrapper](../../exceptionwrapper/)。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## ObjectExt::ToString(T\&) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スカラ型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | T\& | スカラ値を文字列に変換します。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## ObjectExt::ToString(T\&&) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スカラ型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | T\&& | スカラ値を文字列に変換します。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## ObjectExt::ToString(T\&) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 構造体型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | T\& | 構造体値を文字列に変換します。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## ObjectExt::ToString(const T\&) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 構造体型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | 構造体値を文字列に変換します。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## ObjectExt::ToString(T\&&) メソッド


任意の C++ 型で C# の ToString メソッドと同等の機能を提供します。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スカラ型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | T\&& | スカラ値を文字列に変換します。 |

### 戻り値

[String](../../string/) **obj** の文字列表現。

## 参照項目

* クラス [String](../../string/)
* クラス [ObjectExt](../)
* クラス [Nullable](../../nullable/)
* 構造体 [IsSmartPtr](../../issmartptr/)
* 構造体 [IsExceptionWrapper](../../isexceptionwrapper/)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)