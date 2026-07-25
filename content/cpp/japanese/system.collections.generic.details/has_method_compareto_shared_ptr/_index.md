---
title: has_method_compareto_shared_ptr
second_title: Aspose.Slides for C++ API リファレンス
description: "指定された型に CompareTo(SharedPtr<T>) メソッドが存在するか確認します。存在する場合は std::true_type を継承し、存在しない場合は std::false_type を継承します。std::enable_if で使用できます。"
type: docs
weight: 183
url: /ja/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr 構造体


指定された型に CompareTo(SharedPtr<T>) メソッドが存在するか確認します。存在する場合は std::true_type を継承し、存在しない場合は std::false_type を継承します。std::enable_if で使用できます。

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | Equals メソッドの存在をチェックする型。 |
| Sfinae | SFINAE が機能するための形式テンプレート引数。 |

## 参照

* 名前空間 [System::Collections::Generic::Details](../)
* ライブラリ [Aspose.Slides](../../)