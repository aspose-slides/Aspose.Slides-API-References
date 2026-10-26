---
title: IsNull()
second_title: Aspose.Slides for C++ API リファレンス
description: 表現された値が nullptr であるかどうかをチェックします。
type: docs
weight: 27
url: /ja/system.collections.generic.details.castrules/isnull/
---
## System::Collections::Generic::Details::CastRules::IsNull(T) 関数

表現された値が nullptr であるかどうかをチェックします。

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(T)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | 値の型です。 |

### 戻り値

常に false を返します。

## System::Collections::Generic::Details::CastRules::IsNull(SharedPtr\<T\>) 関数

表現された値が nullptr であるかどうかをチェックします。

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(SharedPtr<T> value)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | 値の型です。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../system/sharedptr/)\<T\> | チェック対象の値です。 |

### 戻り値

値が nullptr の場合は true、そうでない場合は false を返します。

## System::Collections::Generic::Details::CastRules::IsNull(Nullable\<T\>) 関数

表現された値が nullptr であるかどうかをチェックします。

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(Nullable<T> value)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | 値の型です。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [Nullable](../../system/nullable/)\<T\> | チェック対象の値です。 |

### 戻り値

値が nullptr の場合は true、そうでない場合は false を返します。

## 関連項目

* Typedef [SharedPtr](../../system/sharedptr/)
* クラス [Nullable](../../system/nullable/)
* 名前空間 [System::Collections::Generic::Details::CastRules](../)
* ライブラリ [Aspose.Slides](../../)