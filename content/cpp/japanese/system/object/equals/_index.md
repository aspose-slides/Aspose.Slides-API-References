---
title: Equals()
second_title: Aspose.Slides for C++ API リファレンス
description: C# の Object.Equals セマンティクスを使用してオブジェクトを比較します。
type: docs
weight: 157
url: /ja/system/object/equals/
---
## Object::Equals(ptr) メソッド

C# [Object.Equals](./) のセマンティクスを使用してオブジェクトを比較します。

```cpp
virtual bool System::Object::Equals(ptr obj)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [ptr](../ptr/) | 現在のオブジェクトと比較するための [Object](../)。 |

### 戻り値

オブジェクトが等しいと見なされる場合は true、そうでなければ false。

## Object::Equals(T1 const\&, T2 const\&) メソッド

C# スタイルで参照型オブジェクトを比較します。

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 比較対象の最初のオブジェクトの型。 |
| T2 | 比較対象の2番目のオブジェクトの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| objA | T1 const\& | 比較対象の最初のオブジェクト。 |
| objB | T2 const\& | 比較対象の2番目のオブジェクト。 |

### 戻り値

オブジェクトが参照または意味的に（[Object.Equals](./) のような比較によって）一致する場合は true、そうでなければ false。

## Object::Equals(T1 const\&, T2 const\&) メソッド

C# スタイルで値型オブジェクトを比較します。

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 比較対象の最初のオブジェクトの型。 |
| T2 | 比較対象の2番目のオブジェクトの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| objA | T1 const\& | 比較対象の最初のオブジェクト。 |
| objB | T2 const\& | 比較対象の2番目のオブジェクト。 |

### 戻り値

利用可能な等価演算子でオブジェクトが等しいとみなされる場合は true、そうでなければ false。

## Object::Equals(float const\&, float const\&) メソッド

IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| objA | **float** const\& | LHS 浮動小数点値。 |
| objB | **float** const\& | RHS 浮動小数点値。 |

### 戻り値

**objA** と **objB** の両方が NaN であるか等しい場合は true、そうでなければ false。

## Object::Equals(double const\&, double const\&) メソッド

IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| objA | **double** const\& | LHS 浮動小数点値。 |
| objB | **double** const\& | RHS 浮動小数点値。 |

### 戻り値

**objA** と **objB** の両方が NaN であるか等しい場合は true、そうでなければ false。

## 参照

* 型定義 [ptr](../ptr/)
* クラス [Object](../)
* 構造体 [IsSmartPtr](../../issmartptr/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)