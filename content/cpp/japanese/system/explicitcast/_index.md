---
title: ExplicitCast()
second_title: Aspose.Slides for C++ API リファレンス
description: 明示的キャストを使用して、ソース型を結果型にキャストします。ソース型と結果型が同じ場合に使用します。
type: docs
weight: 2627
url: /ja/system/explicitcast/
---
## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。ソース型と結果型が同じ場合に使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。シンプルなコンストラクタ風キャストが必要な場合に使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。例外ラッパーに使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。オブジェクトを例外にキャストするために使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。ソースと結果の両方がスマートポインタである場合に使用します（結果型に明示的な `SmartPtr<...>` がない場合）。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(Source) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。生ポインタをスマートポインタにキャストする場合に使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | Source | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。ソースと結果の両方がスマートポインタである場合に使用します（結果型に明示的な `SmartPtr<...>` がある場合）。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。オブジェクトを nullable にアンボックスするために使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。nullable をボックス化するために使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。nullable オブジェクトをアンボックスするために使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。列挙型のボックス化に使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。値型をヒープにコピーし、スマートポインタとして参照すべき場合に使用します（インターフェイス型で制約されたジェネリックで、構造体実装が使用されるシナリオ）。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。値型からインターフェイスを取得するために使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。一般的なボックス化に使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。[System::String](../string/) のボックス化に使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。インターフェイスのアンボックスに使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。一般的なアンボックスに使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。nullptr のキャストに使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## System::ExplicitCast(const Source\&) 関数

明示的キャストを使用して、ソース型を結果型にキャストします。配列間のキャストに使用します。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | ソース型。 |
| Result | 結果型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果。

## 参照

* Typedef [Exception](../exception/)
* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)