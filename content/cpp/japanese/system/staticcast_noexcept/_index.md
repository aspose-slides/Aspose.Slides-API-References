---
title: StaticCast_noexcept()
second_title: Aspose.Slides for C++ API リファレンス
description: SmartPtr オブジェクトに対して static cast を実行します。
type: docs
weight: 2549
url: /ja/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) 関数


[SmartPtr](../smartptr/) オブジェクトに対して static cast を実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | 対象のポインティー型。 |
| TFrom | ソースのポインティー型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合はキャスト結果を返し、そうでない場合は nullptr を返します。

Deprecated
:   後方互換性のために残されています。代わりに AsCast を使用してください。

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) 関数


[WeakPtr](../weakptr/) オブジェクトに対して static cast を実行します。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | 対象のポインティー型。 |
| TFrom | ソースのポインティー型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合はキャスト結果を返し、そうでない場合は nullptr を返します。

Deprecated
:   後方互換性のために残されています。代わりに AsCast を使用してください。

## System::StaticCast_noexcept(const TFrom\&) 関数


Exception オブジェクトに対して static cast を実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | 対象の Exception 型。 |
| TFrom | ソースの Exception 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const TFrom\& | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合はキャスト結果を返し、そうでない場合は nullptr を返します。

Deprecated
:   後方互換性のために残されています。代わりに AsCast を使用してください。

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) 関数


オブジェクトを Exception オブジェクトに static cast を実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | 対象の Exception 型。 |
| TFrom | [Object](../object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合はキャスト結果を返し、そうでない場合は nullptr を返します。

Deprecated
:   後方互換性のために残されています。代わりに AsCast を使用してください。

## 関連項目

* クラス [SmartPtr](../smartptr/)
* クラス [WeakPtr](../weakptr/)
* クラス [Object](../object/)
* 構造体 [IsExceptionWrapper](../isexceptionwrapper/)
* 構造体 [CastResult](../castresult/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)