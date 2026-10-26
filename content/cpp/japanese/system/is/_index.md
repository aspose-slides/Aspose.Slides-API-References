---
title: Is()
second_title: C++ 用 Aspose.Slides API リファレンス
description: "'is' 宣言パターンの変換を実装します。"
type: docs
weight: 2302
url: /ja/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) 関数

'is' 宣言パターンの変換を実装します。

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| PatternT | チェックする型。 |
| ExpressionT | 左側式の型。 |
| ResultT | 結果式の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| left | const ExpressionT\& | チェックされる式。 |
| result | ResultT\& | チェックされた型が代入される変数。 |

### 戻り値

型チェックが成功した場合は true、失敗した場合は false。

## System::Is(const ExpressionT\&, const ConstantT\&) 関数

'is' 定数パターンの変換を実装します。

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| ExpressionT | 左側式の型。 |
| ConstantT | 定数式の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| left | const ExpressionT\& | チェックされる式。 |
| constant | const ConstantT\& | 左側式と比較される式。 |

### 戻り値

型チェックが成功した場合は true、失敗した場合は false。

## System::Is(const E\&, const A\&) 関数

トップレベルのマッチング関数です。パターンを値に適用します。

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| A | パターン型（Details::Pattern から継承する必要があります）。 |
| E | マッチさせる値の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| e | const E\& | マッチさせる対象の値。 |
| a | const A\& | 適用するパターン。 |

### 戻り値

パターンが値にマッチした場合は true、しない場合は false。

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)