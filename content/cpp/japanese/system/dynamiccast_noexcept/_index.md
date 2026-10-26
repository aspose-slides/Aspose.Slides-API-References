---
title: DynamicCast_noexcept()
second_title: Aspose.Slides for C++ API リファレンス
description: 古い非推奨のキャストです。将来のバージョンで削除されます。
type: docs
weight: 2523
url: /ja/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) function

古い非推奨のキャストです。将来のバージョンで削除されます。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | 対象 Exception 型。 |
| TFrom | ソース Exception 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const TFrom\& | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合はキャスト結果を、そうでない場合は nullptr を返します。

## 備考

Exception オブジェクトに対して dynamic cast を実行します。Deprecated
:   後方互換性のために残されています。代わりに AsCast を使用してください。

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) function

[SmartPtr](../smartptr/) オブジェクトに対して dynamic cast を実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | 対象 ポインタ先タイプ。 |
| TFrom | ソース ポインタ先タイプ。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合はキャスト結果を、そうでない場合は nullptr を返します。

非推奨
:   後方互換性のために残されています。代わりに AsCast を使用してください。

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) function

Objects を Exception オブジェクトに dynamic cast を実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | 対象 Exception 型。 |
| TFrom | [Object](../object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合はキャスト結果を、そうでない場合は nullptr を返します。

非推奨
:   後方互換性のために残されています。代わりに AsCast を使用してください。

## 参照

* クラス [SmartPtr](../smartptr/)
* クラス [Object](../object/)
* 構造体 [IsExceptionWrapper](../isexceptionwrapper/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)