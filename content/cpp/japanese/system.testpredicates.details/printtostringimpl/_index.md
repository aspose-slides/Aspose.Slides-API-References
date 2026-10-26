---
title: PrintToStringImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: "System::Object のサブクラスを ToString() メソッドを使用して文字列に出力します。"
type: docs
weight: 14
url: /ja/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) 関数

[System::Object](../../system/object/) サブクラスを ToString() メソッドを使用して文字列に出力します。

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 最終クラス型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 出力するオブジェクトへのポインタ。 |
| s | long long | このパラメータの型に基づいて関数オーバーロードを選択するサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

[String](../../system/string/) 表示は、渡されたオブジェクトの表現、または **value** が null の場合は "nullptr" です。

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) 関数

[System::Object](../../system/object/) サブクラスを ToString() メソッドを使用して文字列に出力します。

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 最終クラス型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | 出力するオブジェクトへのポインタ。 |
| s | long long | このパラメータの型に基づいて関数オーバーロードを選択するサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

[String](../../system/string/) 表示は、渡されたオブジェクトの表現、または **value** が null の場合は "nullptr" です。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 関数

オブジェクトを ToString() メソッドを使用して文字列に出力します。

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) を出力します。 |
| s | long long | このパラメータの型に基づいて関数オーバーロードを選択するサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

[String](../../system/string/) 表示は、渡されたオブジェクトの表現です。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 関数

オブジェクトを PrintTo メソッドを使用して文字列に出力します。

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) を出力します。 |
| s | long long | このパラメータの型に基づいて関数オーバーロードを選択するサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

[String](../../system/string/) 表示は、渡されたオブジェクトの表現です。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 関数

オブジェクトを PrintTo メソッドを使用して文字列に出力します。

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) を出力します。 |
| s | long long | このパラメータの型に基づいて関数オーバーロードを選択するサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

[String](../../system/string/) 表示は、渡されたオブジェクトの表現です。

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) 関数

ペアを文字列に出力します。

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 最初のペア型引数。 |
| T2 | 2番目のペア型引数。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) を出力します。 |
| s | long long | このパラメータの型に基づいて関数オーバーロードを選択するサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

最初と2番目のペア要素の文字列表現を結合したもの。

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) 関数

ペアを文字列に出力します。

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 最初のペア型引数。 |
| T2 | 2番目のペア型引数。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) を出力します。 |
| s | long long | このパラメータの型に基づいて関数オーバーロードを選択するサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

最初と2番目のペア要素の文字列表現を結合したもの。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 関数

STL 形式のコンテナを、その要素（最大 32 個まで）を出力して文字列に変換します。

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) を出力します。 |
| s | long long | このパラメータの型に基づいて関数オーバーロードを選択するサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

含まれる要素の文字列表現を結合したもの。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) 関数

gtest が提供する関数を使用して、他の型を文字列に出力します。

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) を出力します。 |
| s | int | このパラメータの型に基づいて関数オーバーロードを選択するサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

[String](../../system/string/) 表示は、渡されたオブジェクトの表現です。

## 関連項目

* 型定義 [SharedPtr](../../system/sharedptr/)
* クラス [WeakPtr](../../system/weakptr/)
* クラス [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* クラス [Object](../../system/object/)
* 構造体 [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* 構造体 [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* 構造体 [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* 名前空間 [System::TestPredicates::Details](../)
* ライブラリ [Aspose.Slides](../../)