---
title: GetType()
second_title: Aspose.Slides for C++ API リファレンス
description: typeof() の変換を実装します。スマート ポインター用のオーバーロードです。
type: docs
weight: 1
url: /ja/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) メソッド

typeof() の変換を実装します。スマート ポインター用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | ポインタオブジェクト型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) の [TypeInfo](../../typeinfo/) を取得 |

### 戻り値

渡されたオブジェクトの最終クラスを記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType(const T\&) メソッド

typeof() の変換を実装します。構造体用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 構造体型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) の [TypeInfo](../../typeinfo/) を取得 |

### 戻り値

渡されたオブジェクトの最終クラスを記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType(const T\&) メソッド

typeof() の変換を実装します。例外用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 例外型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) の [TypeInfo](../../typeinfo/) を取得 |

### 戻り値

渡されたオブジェクトの最終クラスを記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType(const T) メソッド

typeof() の変換を実装します。プリミティブ型用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プリミティブ型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T | 無視 |

### 戻り値

渡されたオブジェクトの型を記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType(const T) メソッド

typeof() の変換を実装します。[Nullable](../../nullable/) 型用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Nullable](../../nullable/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T | 無視 |

### 戻り値

渡されたオブジェクトの型を記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType() メソッド

typeof() の変換を実装します。プリミティブ型用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プリミティブ型。 |

### 戻り値

指定された型を記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType() メソッド

typeof() の変換を実装します。列挙型用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プリミティブ型。 |

### 戻り値

指定された型を記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType() メソッド

typeof() の変換を実装します。構造体およびポインター用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プリミティブ型。 |

### 戻り値

指定された構造体を記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType() メソッド

typeof() の変換を実装します。[Nullable](../../nullable/) 用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Nullable](../../nullable/) 型。 |

### 戻り値

指定された構造体を記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType() メソッド

typeof() の変換を実装します。MulticastDelegate 用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | MulticastDelegate 型。 |

### 戻り値

指定された構造体を記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType() メソッド

typeof() の変換を実装します。構造体およびポインター用のオーバーロードです。

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プリミティブ型。 |

### 戻り値

指定された構造体または [SmartPtr](../../smartptr/) が要求された場合の指し示す型を記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType(const String\&) メソッド

typeof() の変換を実装します。文字列型用のオーバーロードです。

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プリミティブ型。 |

### 戻り値

[String](../../string/) 型を記述する [TypeInfo](../../typeinfo/) 構造体への const 参照。

## ObjectType::GetType() メソッド

typeof() の変換を実装します。**uint8_t** 用のオーバーロードです。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() メソッド

typeof() の変換を実装します。char16_t 用のオーバーロードです。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() メソッド

typeof() の変換を実装します。**int32_t** 用のオーバーロードです。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() メソッド

typeof() の変換を実装します。**int64_t** 用のオーバーロードです。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() メソッド

typeof() の変換を実装します。bool 用のオーバーロードです。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() メソッド

typeof() の変換を実装します。[Void](../../void/) 用のオーバーロードです。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## 参照

* クラス [ObjectType](../)
* クラス [TypeInfo](../../typeinfo/)
* クラス [String](../../string/)
* 構造体 [IsSmartPtr](../../issmartptr/)
* 構造体 [IsExceptionWrapper](../../isexceptionwrapper/)
* 構造体 [IsNullable](../../isnullable/)
* 構造体 [IsBoxable](../../isboxable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)