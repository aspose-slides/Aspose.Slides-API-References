---
title: StaticCast()
second_title: Aspose.Slides for C++ API リファレンス
description: SmartPtr オブジェクトに対して static cast を実行します。
type: docs
weight: 2562
url: /ja/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) 関数

[SmartPtr](../smartptr/) オブジェクトに対して static cast を実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### 戻り値

Cast result if cast is allowed.

非推奨
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(WeakPtr\<TFrom\> const\&) 関数

[WeakPtr](../weakptr/) オブジェクトに対して static cast を実行します。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Source pointer. |

### 戻り値

Cast result if cast is allowed.

非推奨
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(std::nullptr_t) 関数

null オブジェクトの static cast を実行します。

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | Target pointee type. |

### 戻り値

nullptr.

非推奨
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(TFrom) 関数

算術型の特殊化です。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) 関数

[String](../string/) から [String](../string/) へのキャストを処理します。

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) 関数

算術型の特殊化です。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) 関数

非ポインタオブジェクトに対して static cast を実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const TFrom\& | Source object. |

### 戻り値

Cast result if cast is allowed.

非推奨
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(const TFrom\&) 関数

Exception オブジェクトに対して static cast を実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### 戻り値

Cast result if cast is allowed.

非推奨
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(SmartPtr\<TFrom\>) 関数

Objects を Exception オブジェクトに static cast を実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### 戻り値

Cast result if cast is allowed.

非推奨
:   Left for backwards compatibility. Use ExplicitCast instead.

## 参照

* クラス [SmartPtr](../smartptr/)
* クラス [WeakPtr](../weakptr/)
* クラス [String](../string/)
* クラス [Object](../object/)
* 構造体 [IsExceptionWrapper](../isexceptionwrapper/)
* 構造体 [CastResult](../castresult/)
* 構造体 [IsSmartPtr](../issmartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)