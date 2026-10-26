---
title: AsCast()
second_title: Aspose.Slides for C++ API リファレンス
description: ソース型を結果型に 'as' 演算子キャストを使用して変換します。シンプルなコンストラクタ風キャストが必要な場合に使用されます。
type: docs
weight: 2640
url: /ja/system/ascast/
---
## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。シンプルなコンストラクタ風キャストが必要な場合に使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。ソース型と結果型が同じ場合に使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。例外ラッパーに使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。オブジェクトを例外にキャストするために使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。ソースと結果がともにスマートポインタである場合に使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。変換が利用できない場合は nullptr を返します。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。ソースと結果がともにスマートポインタである場合（結果型に明示的な SmartPtr<...> がある場合）に使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。変換が利用できない場合は nullptr を返します。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。オブジェクトを nullable にアンボックスするために使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。変換が利用できない場合は空の nullable を返します。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。オブジェクト以外の型へのアンボックスは無効です。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

常に null を返します。

## System::AsCast(const Source\&) 関数

オブジェクト以外の型へのアンボックスは無効です。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

常に null を返します。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。nullable オブジェクトをボクシングするために使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。共通オブジェクトをボクシングするために使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。共通オブジェクトをボクシングするために使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。文字列のアンボックスに使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。nullptr のケースに使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。

## System::AsCast(const Source\&) 関数

ソース型を結果型に `as` 演算子キャストを使用して変換します。配列間のキャストに使用されます。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) をキャストします。 |

### 戻り値

キャスト結果です。配列メンバーのいずれかに変換が利用できない場合は nullptr を返します。

## 関連項目

* 型定義 [Exception](../exception/)
* 構造体 [CastResult](../castresult/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)