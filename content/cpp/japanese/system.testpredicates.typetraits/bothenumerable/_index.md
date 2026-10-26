---
title: BothEnumerable
second_title: Aspose.Slides for C++ API リファレンス
description: 両方の型引数が IEnumerable であるかをチェックします。そうであれば、value メンバーは true に設定され、そうでなければ false に設定されます。
type: docs
weight: 144
url: /ja/system.testpredicates.typetraits/bothenumerable/
---
## BothEnumerable typedef


両方の型引数が IEnumerable であるかをチェックします。そうであれば value メンバーは true に設定され、そうでなければ false に設定されます。

```cpp
using System::TestPredicates::TypeTraits::BothEnumerable = typedef std::integral_constant<bool, IsEnumerable<T1>::value && IsEnumerable<T2>::value>
```


## 参照

* 名前空間 [System::TestPredicates::TypeTraits](../)
* ライブラリ [Aspose.Slides](../../)