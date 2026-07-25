---
title: operator==()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 2042
url: /ja/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) function




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) function

指定された[Nullable](../nullable/)オブジェクトが null に等しい値を表すかどうかを判定します。

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | std::nullptr_t | テスト対象の[Nullable](../nullable/)オブジェクトへの定数参照 |

### 戻り値

指定されたオブジェクトが null 値を表す場合は true、そうでない場合は false

## System::operator==(const T1\&, const Nullable\<T2\>\&) function

指定された値が、[Nullable](../nullable/) オブジェクトが表す値に [operator==()](./) を適用して等しいかどうかを判定します。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | 最初の比較対象値の型 |
| T2 | 2番目の比較対象値を表す[Nullable](../nullable/)オブジェクトの基礎型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| some | const T1\& | 最初の比較対象として使用される値への定数参照 |
| other | const [Nullable](../nullable/)\<T2\>\& | 2番目の比較対象として使用される、表現された値を持つ[Nullable](../nullable/)オブジェクトへの定数参照 |

### 戻り値

比較対象が等しい場合は true、そうでない場合は false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) function

2つのスマートポインタを等価比較します。

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| X | 最初のポインタが指す型 |
| Y | 2番目のポインタが指す型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 比較対象の最初のポインタ |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 比較対象の2番目のポインタ |

### 戻り値

ポインタが一致する場合は true、そうでない場合は false

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) function

スマートポインタが null かどうかをチェックします。

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| X | ポインタが指す型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | std::nullptr_t | チェック対象のポインタ |

### 戻り値

ポインタが null の場合は true、そうでない場合は false

## System::operator==(const SmartPtr\<X\>\&, const Y *) function

スマートポインタと単純（C）ポインタの等価比較。

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| X | スマートポインタの型 |
| Y | 単純ポインタの型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 比較対象のスマートポインタ（左） |
| y | const Y * | 比較対象のポインタ（右） |

### 戻り値

ポインタが一致する場合は true、そうでない場合は false

## System::operator==(const X *, const SmartPtr\<Y\>\&) function

スマートポインタと単純（C）ポインタの等価比較。

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| X | 単純ポインタの型 |
| Y | スマートポインタの型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | const X * | 比較対象のポインタ（右） |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 比較対象のスマートポインタ（左） |

### 戻り値

ポインタが一致する場合は true、そうでない場合は false

## System::operator==(T const\&, std::nullptr_t) function

値型オブジェクト（C# の構造体など）が null かどうかをチェックします。

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 値型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | T const\& | チェック対象の[Object](../object/) |

### 戻り値

オブジェクトが null の場合は true、そうでない場合は false

## System::operator==(std::nullptr_t, T const\&) function

値型オブジェクト（C# の構造体など）が null かどうかをチェックします。

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 値型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | std::nullptr_t | チェック対象の[Object](../object/) |

### 戻り値

オブジェクトが null の場合は true、そうでない場合は false

## System::operator==(Chars\&, const String\&) function

[String](../string/)比較。

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Chars | [String](../string/)リテラル型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | Chars\& | 比較対象の[String](../string/)リテラル |
| right | const [String](../string/)\& | 比較対象の[String](../string/) |

### 戻り値

文字列が一致する場合は true、そうでない場合は false

## System::operator==(T\&, const String\&) function

[String](../string/)比較。

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [String](../string/)ポインタ型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | T\& | 比較対象の[String](../string/)ポインタ |
| right | const [String](../string/)\& | 比較対象の[String](../string/) |

### 戻り値

文字列が一致する場合は true、そうでない場合は false

## System::operator==(const SharedPtr\<Object\>\&, const String\&) function

[Object](../object/)と文字列の比較。

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | 文字列に変換して比較する[Object](../object/) |
| right | const [String](../string/)\& | 比較対象の[String](../string/) |

### 戻り値

オブジェクトの文字列表現が文字列と等しい場合は true、そうでない場合は false

## System::operator==(std::nullptr_t, const String\&) function

文字列が null かどうかをチェックします。

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | std::nullptr_t | チェック対象の[String](../string/) |

### 戻り値

文字列が null の場合は true、そうでない場合は false

## System::operator==(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) function

現在のオブジェクトと指定されたオブジェクトが表す URI が等しいかどうかを判定します。

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 比較対象の最初の[Uri](../uri/)オブジェクト |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 比較対象の2番目の[Uri](../uri/)オブジェクト |

### 戻り値

URI が等しい場合は true、そうでない場合は false

## 関連項目

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)