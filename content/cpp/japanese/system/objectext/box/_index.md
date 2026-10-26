---
title: Box()
second_title: Aspose.Slides for C++ API リファレンス
description: Object に変換するための値型をボックス化します。列挙型の実装です。
type: docs
weight: 40
url: /ja/system/objectext/box/
---
## ObjectExt::Box(const T\&) メソッド


[Object](../../object/) に変換するための値型をボックス化します。列挙型の実装です。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Enum](../../enum/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) をボックス化する値。 |

### 戻り値

ボックス化された値を保持するオブジェクトへのスマートポインタ。

## ObjectExt::Box(const T\&) メソッド


[Object](../../object/) に変換するための値型をボックス化します。列挙型以外の実装です。

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 値型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | ボックス化する値。 |

### 戻り値

ボックス化された値を保持するオブジェクトへのスマートポインタ。

## ObjectExt::Box(const T\&) メソッド


[Nullable](../../nullable/) 型を [Object](../../object/) に変換するためにボックス化します。

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 値型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | ボックス化する値。 |

### 戻り値

ボックス化された値を保持するオブジェクトへのスマートポインタ。

## ObjectExt::Box(const String\&) メソッド


文字列値をボックス化します。

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | ボックス化する値。 |

### 戻り値

ソース文字列が null の場合、ボックス化された値または null を返します。

## See Also

* クラス [SmartPtr](../../smartptr/)
* クラス [Object](../../object/)
* クラス [ObjectExt](../)
* クラス [String](../../string/)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)