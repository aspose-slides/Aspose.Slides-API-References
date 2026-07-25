---
title: CastEnumerableTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された列挙可能オブジェクトの要素を別の型に明示的にキャストします。
type: docs
weight: 2965
url: /ja/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) 関数

指定された列挙可能オブジェクトの要素を別の型に明示的にキャストします。

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| To | 列挙可能オブジェクトの要素を静的にキャストする型 |
| From | 列挙可能オブジェクトの型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| enumerable | const From\& | キャストする要素を含む Enumerable オブジェクト |

### 戻り値

新しいコレクションへのポインタで、**enumerable** の要素に相当する **To** 型の要素を含みます。

## System::CastEnumerableTo(const From\&) 関数

指定された列挙可能オブジェクトの要素を別の型に明示的にキャストします。

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| To | 列挙可能オブジェクトの要素を静的にキャストする型 |
| From | 列挙可能オブジェクトの型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| enumerable | const From\& | 定義された get_Count メソッドを持つ Enumerable オブジェクトの継承者で、キャストする要素を含んでいます |

### 戻り値

新しいコレクションへのポインタで、**enumerable** の要素に相当する **To** 型の要素を含みます。

## 参照

* クラス [ListPtr](../../system.collections.generic/listptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)