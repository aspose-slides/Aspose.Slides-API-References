---
title: BothArrayOrList
second_title: Aspose.Slides for C++ API リファレンス
description: 両方の型引数が配列またはリストかどうかをチェックします。もしそうであれば、value メンバーが true に設定され、そうでなければ false に設定されます。
type: docs
weight: 131
url: /ja/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

両方の型引数が配列またはリストかどうかを確認します。もしそうであれば、value member が true に設定され、そうでなければ false に設定されます。

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## 参照

* 名前空間 [System::TestPredicates::TypeTraits](../)
* ライブラリ [Aspose.Slides](../../)