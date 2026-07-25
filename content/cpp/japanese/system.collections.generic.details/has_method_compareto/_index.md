---
title: has_method_compareto
second_title: Aspose.Slides の C++ API リファレンス
description: "指定された型に CompareTo メソッドが存在するかを確認します。存在する場合は std::true_type を継承し、存在しない場合は std::false_type を継承します。std::enable_if で使用できます。"
type: docs
weight: 170
url: /ja/system.collections.generic.details/has_method_compareto/
---
## has_method_compareto struct

指定された型に CompareTo メソッドが存在するかを確認します。存在する場合は std::true_type を継承し、存在しない場合は std::false_type を継承します。std::enable_if で使用できます。

```cpp
template<typename T,typename Sfinae>class has_method_compareto : public std::false_type
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | Equals メソッドの存在をチェックする型。 |
| Sfinae | SFINAE が機能するための形式テンプレート引数。 |

## 参照

* 名前空間 [System::Collections::Generic::Details](../)
* ライブラリ [Aspose.Slides](../../)