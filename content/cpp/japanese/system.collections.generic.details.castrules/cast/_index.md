---
title: Cast()
second_title: Aspose.Slides for C++ API リファレンス
description: ソース型を結果型にキャストします。ソース型と結果型が同じ場合に使用します。
type: docs
weight: 14
url: /ja/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) 関数

ソース型を結果型にキャストします。ソース型と結果型が同じ場合に使用します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Source | ソース型です。 |
| Result | 結果型です。 |

### 戻り値

キャスト結果です。

## System::Collections::Generic::Details::CastRules::Cast(Source) 関数

ソース型を結果型にキャストします。ソース型が結果型に静的にキャストできる場合に使用します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Source | ソース型です。 |
| Result | 結果型です。 |

### 戻り値

キャスト結果です。

## System::Collections::Generic::Details::CastRules::Cast(Source) 関数

ソース型を結果型にキャストします。型が同じでなく、ソース型を結果型に静的にキャストできない場合に使用します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Source | ソース型です。 |
| Result | 結果型です。 |

### 戻り値

キャスト結果です。

## System::Collections::Generic::Details::CastRules::Cast(Source) 関数

ソース型を結果型にキャストします。ソース型が [Nullable](../../system/nullable/) クラスインスタンスにボックス化される場合に使用します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Source | ソース型です。 |
| Result | 結果型です。 |

### 戻り値

キャスト結果です。

## System::Collections::Generic::Details::CastRules::Cast(Source) 関数

ソース型を結果型にキャストします。ソース型が [Nullable](../../system/nullable/) クラスインスタンスからアンボックス化される場合に使用します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Source | ソース型です。 |
| Result | 結果型です。 |

### 戻り値

キャスト結果です。

## System::Collections::Generic::Details::CastRules::Cast(Source) 関数

ソース型を結果型にキャストします。ソース型が [Object](../../system/object/) クラスインスタンスにボックス化される場合に使用します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Source | ソース型です。 |
| Result | 結果型です。 |

### 戻り値

キャスト結果です。

## System::Collections::Generic::Details::CastRules::Cast(Source) 関数

ソース型を結果型にキャストします。ソース型が [Object](../../system/object/) クラスインスタンスからアンボックス化される場合に使用します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Source | ソース型です。 |
| Result | 結果型です。 |

### 戻り値

キャスト結果です。

## System::Collections::Generic::Details::CastRules::Cast(Source) 関数

ソース型を結果型にキャストします。キャストが無効であるか、変換が明示的な場合に使用します。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Source | ソース型です。 |
| Result | 結果型です。 |

### 戻り値

キャスト結果です。

## 参照

* 構造体 [CastType](../casttype/)
* 名前空間 [System::Collections::Generic::Details::CastRules](../)
* ライブラリ [Aspose.Slides](../../)