---
title: IsArray
second_title: Aspose.Slides for C++ API リファレンス
description: "型が System::Array の特殊化かどうかを確認します。もしそうであれば、value メンバーは true に設定され、そうでなければ false に設定されます。"
type: docs
weight: 105
url: /ja/system.testpredicates.typetraits/isarray/
---
## IsArray typedef

型が [System::Array](../../system/array/) の特殊化かどうかをチェックします。もしそうであれば、value メンバーは true に設定され、そうでなければ false に設定されます。

```cpp
using System::TestPredicates::TypeTraits::IsArray = typedef std::is_same<T, System::Array<typename T::ValueType> >
```

## 参照

* 名前空間 [System::TestPredicates::TypeTraits](../)
* ライブラリ [Aspose.Slides](../../)