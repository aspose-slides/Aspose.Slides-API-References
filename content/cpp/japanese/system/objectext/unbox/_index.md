---
title: Unbox()
second_title: Aspose.Slides for C++ API リファレンス
description: Object に変換した後に値型をアンボックスします。enum 型の実装です。
type: docs
weight: 53
url: /ja/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) メソッド

[Object](../../object/) に変換した後に値型をアンボックスします。enum 型の実装です。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Enum](../../enum/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) をアンボックスします。 |

### 戻り値

[Enum](../../enum/) 値。

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) メソッド

[Object](../../object/) に変換した後に値型をアンボックスします。非 enum および非 nullable 型の実装です。

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) をアンボックスします。 |

### 戻り値

アンボックスされた値。

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) メソッド

[Object](../../object/) に変換した後に値型をアンボックスします。非 enum および非 nullable 型の実装です。

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) をアンボックスします。 |

### 戻り値

アンボックスされた値。

## ObjectExt::Unbox(E) メソッド

enum 型を整数にアンボックスします。

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 目的の整数型。 |
| E | 元の enum 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| e | E | アンボックスする値。 |

### 戻り値

enum の整数表現。

## ObjectExt::Unbox(E) メソッド

enum 型を変換します。

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 目的の enum 型。 |
| E | 元の enum 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| e | E | アンボックスする値。 |

### 戻り値

変換された enum 値。

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) メソッド

文字列値をアンボックスします。

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) をアンボックスします。 |

### 戻り値

[String](../../string/) のボックスされた文字列の表現です。ボックスされた文字列が null の場合は null になる可能性があります。

## 参照

* クラス [SmartPtr](../../smartptr/)
* クラス [Object](../../object/)
* クラス [ObjectExt](../)
* クラス [String](../../string/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)