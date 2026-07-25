---
title: IsList
second_title: Aspose.Slides for C++ API リファレンス
description: "型が System::Collections::Generic::List の特殊化かどうかを確認します。もしそうであれば、value メンバーは true に設定され、そうでなければ false に設定されます。"
type: docs
weight: 118
url: /ja/system.testpredicates.typetraits/islist/
---
## IsList typedef


タイプが [System::Collections::Generic::List](../../system.collections.generic/list/) の特殊化かどうかを確認します。もしそうであれば、value メンバーは true に設定され、そうでなければ false に設定されます。

```cpp
using System::TestPredicates::TypeTraits::IsList = typedef std::is_same<T, System::Collections::Generic::List<typename T::ValueType> >
```


## 参照

* 名前空間 [System::TestPredicates::TypeTraits](../)
* ライブラリ [Aspose.Slides](../../)