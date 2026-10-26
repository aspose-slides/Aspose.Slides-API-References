---
title: DoTryFinally()
second_title: Aspose.Slides for C++ API リファレンス
description: C# の try[-catch]-finally 文の動作をエミュレートする単一の関数です。translator のオプション finally_statement_as_lambda が true に設定されている状態で C# の try[-catch]-finally 文を変換すると、このステートメントはこのメソッドの呼び出しに変換されます。
type: docs
weight: 2445
url: /ja/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) 関数

C# の try[-catch]-finally 文の動作をエミュレートする単一の関数です。translator のオプション finally_statement_as_lambda が true に設定されている状態で C# の try[-catch]-finally 文を変換すると、このステートメントはこのメソッドの呼び出しに変換されます。

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | エミュレートされる try[-catch]-finally 文の try[-catch] 部分を実装する関数オブジェクトの型 |
| F | エミュレートされる try[-catch]-finally 文の finally 部分を実装する関数オブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tryBlock | T\&& | エミュレートされる try[-catch]-finally 文の try[-catch] 部分を実装する関数オブジェクトで、その本体に実装が含まれます |
| finallyBlock | F\&& | エミュレートされる try[-catch]-finally 文の finally 部分を実装する関数オブジェクトで、その本体に実装が含まれます |

## System::DoTryFinally(T\&&, F\&&) 関数

C# の try[-catch]-finally 文の動作をエミュレートする単一の関数です。translator のオプション finally_statement_as_lambda が true に設定されている状態で C# の try[-catch]-finally 文を変換すると、このステートメントはこのメソッドの呼び出しに変換されます。このオーバーロードは、try[-catch]-finally 文の try[-catch] 部分を実装する関数オブジェクトの戻り値が bool である場合を扱います。

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | エミュレートされる try[-catch]-finally 文の try[-catch] 部分を実装する関数オブジェクトの型 |
| F | エミュレートされる try[-catch]-finally 文の finally 部分を実装する関数オブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tryBlock | T\&& | エミュレートされる try[-catch]-finally 文の try[-catch] 部分を実装する関数オブジェクトで、その本体に実装が含まれます |
| finallyBlock | F\&& | エミュレートされる try[-catch]-finally 文の finally 部分を実装する関数オブジェクトで、その本体に実装が含まれます |

## System::DoTryFinally(T\&&, F\&&) 関数

C# の try[-catch]-finally 文の動作をエミュレートする単一の関数です。translator のオプション finally_statement_as_lambda が true に設定されている状態で C# の try[-catch]-finally 文を変換すると、このステートメントはこのメソッドの呼び出しに変換されます。このオーバーロードは、try[-catch]-finally 文の try[-catch] 部分を実装する関数オブジェクトの戻り値が bool& である場合を扱います。

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | エミュレートされる try[-catch]-finally 文の try[-catch] 部分を実装する関数オブジェクトの型 |
| F | エミュレートされる try[-catch]-finally 文の finally 部分を実装する関数オブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tryBlock | T\&& | エミュレートされる try[-catch]-finally 文の try[-catch] 部分を実装する関数オブジェクトで、その本体に実装が含まれます |
| finallyBlock | F\&& | エミュレートされる try[-catch]-finally 文の finally 部分を実装する関数オブジェクトで、その本体に実装が含まれます |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)