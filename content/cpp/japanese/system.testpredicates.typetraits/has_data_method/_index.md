---
title: has_data_method
second_title: Aspose.Slides for C++ API リファレンス
description: "型に data() メソッドがあるかどうかをチェックします。ある場合は std::true_type を継承し、そうでない場合は std::false_type を継承します。"
type: docs
weight: 1
url: /ja/system.testpredicates.typetraits/has_data_method/
---
## has_data_method struct

型に data() メソッドがあるかどうかをチェックします。ある場合は std::true_type を継承し、そうでない場合は std::false_type を継承します。

```cpp
template<typename T,typename Enable>class has_data_method : public std::false_type
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | 確認する型。 |
| Enable | SFINAE が機能するための形式引数。 |

## See Also

* 名前空間 [System::TestPredicates::TypeTraits](../)
* ライブラリ [Aspose.Slides](../../)