---
title: CanCast()
second_title: Aspose.Slides for C++ API リファレンス
description: キャストの可能性を確認します。
type: docs
weight: 40
url: /ja/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) 関数

キャストの可能性を確認します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 戻り値

キャスト後に nullptr ではない値が返された場合は true、そうでない場合は false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 関数

キャストの可能性を確認します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 戻り値

キャスト後に nullptr ではない値が返された場合は true、そうでない場合は false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 関数

キャストの可能性を確認します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 戻り値

キャスト後に nullptr ではない値が返された場合は true、そうでない場合は false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 関数

キャストの可能性を確認します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 戻り値

常に true を返します。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 関数

キャストの可能性を確認します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 戻り値

キャスト後に nullptr ではない値が返された場合は true、そうでない場合は false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 関数

キャストの可能性を確認します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 戻り値

常に true を返します。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 関数

キャストの可能性を確認します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 戻り値

キャスト操作が成功した場合は true、そうでない場合は false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 関数

キャストの可能性を確認します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 戻り値

常に false を返します。

## 参照

* 構造体 [CastType](../casttype/)
* 名前空間 [System::Collections::Generic::Details::CastRules](../)
* ライブラリ [Aspose.Slides](../../)