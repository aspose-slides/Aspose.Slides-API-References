---
title: has_print_to_method
second_title: Aspose.Slides の C++ API リファレンス
description: "指定された型を最初の引数として受け取る PrintTo 関数のオーバーロードがあるかどうかをチェックします。オーバーロードが存在する場合は std::true_type を継承し、存在しない場合は std::false_type を継承します。"
type: docs
weight: 27
url: /ja/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method 構造体

指定された型を最初の引数として受け取る PrintTo 関数のオーバーロードがあるかどうかをチェックします。オーバーロードが存在する場合は std::true_type を継承し、存在しない場合は std::false_type を継承します。

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | チェックする型。 |
| Enable | SFINAE が機能するための形式引数。 |

## 参照

* 名前空間 [System::TestPredicates::TypeTraits](../)
* ライブラリ [Aspose.Slides](../../)