---
title: DynamicCast()
second_title: Aspose.Slides for C++ API リファレンス
description: Exception オブジェクトに対して動的キャストを実行します。
type: docs
weight: 2536
url: /ja/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) 関数

Exception オブジェクトに対して動的キャストを実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```

### テンプレート パラメーター

| Parameter | Description |
| --- | --- |
| TTo | 対象 Exception 型。 |
| TFrom | ソース Exception 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合のキャスト結果。

非推奨
:   下位互換性のために残されています。代わりに ExplicitCast を使用してください。

## System::DynamicCast(SmartPtr\<TFrom\> const\&) 関数

[SmartPtr](../smartptr/) オブジェクトに対して動的キャストを実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```

### テンプレート パラメーター

| Parameter | Description |
| --- | --- |
| TTo | 対象 ポインテッド型。 |
| TFrom | ソース ポインテッド型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合のキャスト結果。

非推奨
:   下位互換性のために残されています。代わりに ExplicitCast を使用してください。

## System::DynamicCast(SmartPtr\<TFrom\>) 関数

キャストを使用してボックス化された enum をアンボックスします。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### テンプレート パラメーター

| Parameter | Description |
| --- | --- |
| TTo | 対象 enum 型。 |
| TFrom | ソース ポインテッド型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | データをアンボックスするオブジェクトへのポインタ。 |

### 戻り値

アンボックスされた enum の値。

非推奨
:   下位互換性のために残されています。代わりに ExplicitCast を使用してください。

## System::DynamicCast(std::nullptr_t) 関数

null オブジェクトに対して動的キャストを実行します。

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### テンプレート パラメーター

| Parameter | Description |
| --- | --- |
| TTo | 対象 ポインテッド型。 |

### 戻り値

nullptr。

非推奨
:   下位互換性のために残されています。代わりに ExplicitCast を使用してください。

## System::DynamicCast(TFrom\&) 関数

ポインタでないオブジェクトに対して動的キャストを実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### テンプレート パラメーター

| Parameter | Description |
| --- | --- |
| TTo | 対象 型。 |
| TFrom | ソース 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | TFrom\& | ソース オブジェクト。 |

### 戻り値

キャスト結果。

非推奨
:   下位互換性のために残されています。代わりに ExplicitCast を使用してください。

## System::DynamicCast(SmartPtr\<TFrom\>) 関数

Objects を Exception オブジェクトに対して動的キャストを実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### テンプレート パラメーター

| Parameter | Description |
| --- | --- |
| TTo | 対象 Exception 型。 |
| TFrom | [Object](../object/) 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合のキャスト結果。

非推奨
:   下位互換性のために残されています。代わりに ExplicitCast を使用してください。

## System::DynamicCast(TFrom) 関数

IntPtr からポインタへの動的キャストを実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### テンプレート パラメーター

| Parameter | Description |
| --- | --- |
| TTo | 対象 型。 |
| TFrom | ソース 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | TFrom | ソース IntPtr 値。 |

### 戻り値

キャスト結果。

非推奨
:   下位互換性のために残されています。代わりに ExplicitCast を使用してください。

## 参照

* クラス [SmartPtr](../smartptr/)
* クラス [Object](../object/)
* 構造体 [IsExceptionWrapper](../isexceptionwrapper/)
* 構造体 [CastResult](../castresult/)
* 構造体 [IsSmartPtr](../issmartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)